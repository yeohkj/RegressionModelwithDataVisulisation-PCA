# RegressionModelwithDataVisulisation-PCA

**Question 1 - Regression and regularisation**

Given a dataset, use scikit-learn to create regression models to predict the value of variable Y listed in the last column of the dataset, based on the values of all other variables. You need to choose which type of regression to do, whether to use regularisation and if so, what kind, and how to validate your results. Alternate portions of your code with appropriate text explaining what each part of the code aims to achieve, and comment on the results, and how they inform your decisions.

**Question 2 - Descriptive statistics, data visualisation and PCA**

The population of Square Island (Fig. 1), a territory perfectly aligned with the four cardinal
directions (North, East, South, West), was established in three migration waves, which are
reflected in the genetic makeup of the inhabitants.
The earliest wave preceded the other two by a long margin. It consisted of hunter-gatherers
whose genetic makeup had been distributed uniformly across the whole island before the next
two waves arrived. The second migration wave entered the island through an isthmus, that is, a

![image](https://user-images.githubusercontent.com/61396956/123650592-a1349e80-d822-11eb-9895-2cc1c6aa7713.png)

narrow strip of land, which temporarily connected the South-Western corner of the island with
the nearest continent during a mini ice age period when the sea levels dropped. The new
arrivals were farmers who started to spread slowly, breaking new ground for farming and
advancing by about one mile with each generation. The third and last migration wave brought a
population of seafarers to the island’s shores.
We have data on the relative frequency of 7 genes (proportion of population with a given gene
expressed as a number between 0 and 1) as measured at various locations on the island. These
locations are spaced at equal intervals along the X coordinate (West to East) and Y coordinate
(South to North) over the entire area. Genes 1 and 2 are mutually exclusive alternatives (alleles)
that can appear at one specific position in the genome known as Locus 1. The same is valid for
genes 3 and 4, which are the only 2 alternatives for Locus 2, and genes 5, 6 and 7, which are the
three alleles that can appear in Locus 3. This means that in any given location (x,y) the relative
frequencies of Gene 1 and Gene 2 add up to 1, and so do the relative frequencies of Genes 3
and 4, and Genes 5, 6 and 7. The data is available as a CSV table (see file sqisland.csv)
with a header row and 9 columns, representing the attributes listed in Table 1.
So, we may know, for instance, that in a given location 70% of the population have Gene 1, and
the remaining 30% have Gene 2. Similarly, the proportion of the population in that location with
Gene 3 may be, say, 40%, which leaves the remaining 60% carrying Gene 4. Finally, the
individuals in that location that carry one of the genes 5–7 may be split as 25% : 40% : 35%.
Remember, each of the 3 migration waves brought a new population with its own specific genetic
makeup (relative gene frequencies) that mixed with the existing population over time.

![image](https://user-images.githubusercontent.com/61396956/123650696-bb6e7c80-d822-11eb-936f-4b8c24758673.png)

For each of the 7 genes, produce a contour plot visualising how its relative frequency
varies across the whole island. 

Study the contour plots to form a hypothesis about the most common alleles for
Locus 1 and Locus 2 in: (a) the hunter-gatherers’ population; (b) in the farmers’
population.

Describe any significant characteristics of the genetic makeup of the population of
seafarers.

Calculate and display the variance of each of the 7 gene attributes

Calculate the Pearson correlation between (a) Gene 1 and Gene 4; (b) Gene 1 and
Gene 5. State if the null hypothesis of non-correlation can be rejected for either pair at the
95% significance level. Do these results agree with your hypothesis about the genetic
makeup of the farmers from the second wave?

Apply principal component analysis (PCA) to the data consisting of the relative
frequencies of Genes 1–7. Transform the data using all 7 principal components and
calculate and display the variance for each of them.

Compare the sums of variances of all 7 attributes before and after transforming the
data via PCA. Comment briefly whether the result can be expected or not and why.

Plot the first two PCA components as contour plots visualising the relative frequencies
of each component across the island. Compare the result to the contour plots for Gene 1
and Gene 3 (data before PCA). Which of the two pairs of plots do you find more helpful for
the task of reconstructing the waves of migration? Do you expect the same result for a
realistic data set with hundreds of genes and why?


