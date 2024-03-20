# Analyze A/B Test Results

### Introduction
The Analyze A/B Test Results project is part of Udacity's Data Analyst Nanodegree program. The objective of this project is to analyze the results of an A/B test conducted by a company to determine whether they should implement a new page on their e-commerce website or keep the old page.

### Part I - Probability
In this section, the project begins by exploring the dataset and calculating basic probabilities related to conversions and user interactions with the new and old pages.

### Part II - A/B Test
The A/B test section delves into hypothesis testing to determine whether the new page leads to a significant increase in conversions compared to the old page. The analysis involves simulating the null hypothesis and comparing it with the observed data to draw conclusions about the effectiveness of the new page.

### Part III - Regression
In this final part, the project utilizes logistic regression to perform the same analysis as the previous A/B test, but with a different approach.

b. The logistic regression model is fitted using statsmodels to examine the significance of the page type (old or new) on conversion rates.

d. The summary of the logistic regression model is provided, revealing coefficients, standard errors, z-scores, and p-values associated with each predictor variable.

f. Consideration is given to the advantages and disadvantages of adding additional terms into the regression model. While adding more variables could capture potential interactions and avoid bias, it also risks multicollinearity and increased complexity.

g. Investigation is conducted to determine whether the country of the user has an impact on conversion rates. While dummy variables for different countries are included in the regression model, the p-values suggest that the country does not significantly affect conversions.

h. Furthermore, interactions between page and country are explored to assess their effects on conversion rates. However, the results indicate that these interactions do not have significant effects on conversions.

### Conclusions
Through the experiments conducted in this project, I wanted to determine whether the company should adopt the new page, retain the old page, or continue the experiment. Despite testing through various methodologies including hypothesis testing and logistic regression, the findings failed to provide sufficient evidence to support the implementation of the new page.

Additionally, the analysis was conducted with some limitations, including missing data which required dropping inaccurate rows. This may have influenced the results, so further investigation with complete datasets would be helpful in determining the decision in the future.

Ultimately, the project concludes that neither the new nor the old page significantly outperforms the other in terms of conversion rates. 
