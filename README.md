# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains a Jupyter Notebook focused on the initial Exploratory Data Analysis (EDA) of the classic Titanic dataset. The goal of this analysis is to load, inspect, and summarize the core structural characteristics of the dataset before applying machine learning workflows.

## 🚀 Overview

The notebook demonstrates basic data assessment techniques using foundational Python data science libraries. It loads the dataset, inspects its shape, checks for missing data summary statistics, and categorizes columns into numerical and categorical components.

### Data Insights Summary
* **Dataset Shape:** 891 rows and 12 columns.
* **Missing Data Identified:** 
  * `Age` (177 missing values)
  * `Cabin` (687 missing values)
  * `Embarked` (2 missing values)
* **Feature Types:**
  * **Numerical Columns:** `PassengerId`, `Survived`, `Pclass`, `Age`, `SibSp`, `Parch`, `Fare`
  * **Categorical Columns:** `Name`, `Sex`, `Ticket`, `Cabin`, `Embarked`

---

## 🛠️ Requirements & Installation

To run this notebook locally or in an environment like Google Colab, you need Python installed along with the following data analysis libraries:

```bash
pip install numpy pandas
