# DataAnalysis_project
# Titanic Dataset Exploratory Data Analysis (EDA)

## Project Overview
This project performs a complete Exploratory Data Analysis (EDA) on the Titanic dataset using Python.  
The main goal is to inspect the dataset, clean missing values, visualize important patterns, and extract meaningful insights related to passenger survival.

The project follows a clear data analysis workflow starting from data loading and cleaning, followed by univariate and bivariate analysis, and ending with correlation analysis and insights.

---

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## Dataset
The Titanic dataset is loaded directly from the Seaborn library using:

```python
sns.load_dataset("titanic")
Project Workflow
1. Data Loading and Inspection

Load the dataset

Display first and last rows

Check data types and structure

Generate statistical summaries

2. Data Cleaning

Remove duplicate rows

Handle missing values:

Numerical features filled using median

Categorical features filled using mode

Ensure no missing values remain in key features

3. Exploratory Data Analysis

Univariate analysis using histograms, boxplots, and count plots

Bivariate analysis comparing survival by gender, class, age, and fare

Correlation analysis using a heatmap

Key Findings

Female passengers had a much higher survival rate than males

First class passengers had the highest probability of survival

Younger passengers were more likely to survive

Fare showed large variation and several outliers

Gender and passenger class have the strongest relationship with survival

After cleaning, the dataset contains no missing values in important features

Output

The cleaned dataset is saved as:

titanic_cleaned.csv


The dataset is ready for further analysis or machine learning modeling.
