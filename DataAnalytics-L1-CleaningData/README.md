# Data Cleaning — Cafe Sales Dataset

## Project Overview
This project was completed as part of the Oasis Infobyte (OIBSIP) Data Analytics Internship, Level 1, Task 3: Cleaning Data.

The objective was to inspect and clean a cafe sales dataset using Python and pandas.

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
The original dataset, `dirty_cafe_sales.csv`, contains 10,000 rows and 8 columns related to cafe transactions.

## Data Cleaning Steps
1. Inspected the dataset and identified missing and invalid values.
2. Converted invalid markers such as `ERROR` and `UNKNOWN` into missing values where appropriate.
3. Recovered numerical values where sufficient information was available.
4. Removed 58 rows with unresolved missing numerical transaction values.
5. Checked for duplicate rows.
6. Standardized text values, including Location labels.
7. Converted Transaction Date to datetime format.
8. Detected outliers using the Interquartile Range (IQR) method.
9. Validated the relationship between Quantity, Price Per Unit, and Total Spent.
10. Generated a before-and-after data quality report and exported the cleaned dataset.

## Results
- Original records: 10,000
- Cleaned records: 9,942
- Rows removed: 58
- Columns retained: 8
- Duplicate rows remaining: 0
- Missing values in the three numerical transaction columns: 0
- Outliers detected in Total Spent: 267, retained after inspection

Some missing values remain in categorical columns and transaction dates. These were documented rather than filled with invented information.

## Project Files
- `dirty_cafe_sales.csv` — Original dataset
- `cleaned_cafe_sales.csv` — Cleaned dataset
- `Data_Cleaning_Task3.ipynb` — Jupyter Notebook containing code, outputs, and explanations

## Conclusion
The project demonstrates data inspection, missing-value handling, data type conversion, text standardization, duplicate checking, outlier detection, validation, and CSV export using Python.

**Internship:** Oasis Infobyte (OIBSIP)  
**Track:** Data Analytics  
**Task:** Level 1 — Task 3: Cleaning Data
