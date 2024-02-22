# Walmart Business Case Study


## Walmart Data: Cleaning, Analysis and Visualization
Data Analysis and Visualization on Walmart Data to provide insights and recommendations to improve their userbase.

Column | Description | 
--- | --- 
User_ID | User ID of the Customer | 
Product ID | Product ID of the Purchased Product | 
Gender | Gender of the Customer (Male/Female) | 
Age | Age of the Customer (in bins) | 
Occupation | 	Occupation of the Customer (Masked) |
City_Category | Category of the City (A,B,C) | 
StayInCurrentCityYears | Number of years stay in current city | 
Marital_Status |  Marital Status (0 - Unmarried / 1 - Married) | 
ProductCategory | Product Category (Masked) | 
Purchase | Purchase Amount | 


The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

## Performed following Tasks
1. Data Cleaning
2. Analysis
3. Visualization

- Observations on the shape of data, data types of all the attributes, conversion of categorical attributes to 'category', missing value detection, statistical summary

- Non-Graphical Analysis: Value counts and unique attributes ​
- Visual Analysis - Univariate, Bivariate after pre-processing of the data
- For continuous variable(s): Distplot, countplot, histogram for univariate analysis 
- For categorical variable(s): Boxplot 
- For correlation: Heatmaps, Pairplots 
- Missing Value & Outlier check

- Insights based on Non-Graphical and Visual Analysis
  
    . Comments on the range of attributes
  
    . Comments on the distribution of the variables and relationship between them
  
    . Comments for each univariate and bivariate plot

- Answering questions
  
  . Are women spending more money per transaction than men? Why or Why not?
  
  . Confidence intervals and distribution of the mean of the expenses by female and male customers
  
  . Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements?
  
  . Results when the same activity is performed for Married vs Unmarried
  
  . Results when the same activity is performed for Age
  

- Business Insights - Insights and Recommendations based on exploration and CLT
  
  . Distribution of the variables and relationship between them
  . Each univariate and bivariate plots


### Description about files in repository <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Down%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Down Light Skin Tone" width="30" height="30" />:


**Walmart Business Case Study.ipynb** - Colaboratory notebook containing the code for analysis
