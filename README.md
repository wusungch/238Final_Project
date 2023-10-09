# IBM-Employee-Attrition-Statistical-Analysis-using-R
Research Project Overview:
* Performed data analysis and statistical tests on IBM employee data to assess the factors of employee attrition using R. 
* R Packages used: tidyverse, ggplot2, gridExtra

Research questions: 
#1: Do employees that attrit have lower average monthly income and job satisfaction compared to those that do not?
#2: Is there any association between a male IBM sales employee's total years worked and their monthly income?

Summary: 
Data Analysis:
* 		Scatter plot and Simple Linear Regression (SLR) for male employees in the sales department to explore the relationship between total work years and monthly income.
* 		Checked the normality of residuals from the SLR model using histograms and QQ plots.
* 		Conducted two population hypothesis tests and bootstrapped confidence intervals to compare the average monthly income of employees leaving IBM with those staying.

SLR Model Findings:
* The model showed a positive linear relationship between monthly income and total work years.
* About 56.57% of the variability in monthly income can be explained by total work years.
* The p-value indicated a significant correlation between monthly income and work experience.

Confidence Intervals:
* Computed 95% confidence intervals for intercept and slope of the SLR model.

The file includes data analysis, hypothesis testing, and SLR modeling to answer research questions related to IBM employee attrition data.
