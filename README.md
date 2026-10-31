# Day 19 - Handle Missing Values

## Project Description
This project focuses on handling missing values in a dataset using Python and Pandas. The Titanic dataset is used to identify, analyse, and handle missing values through appropriate data preprocessing techniques.

## Objective
To learn basic data preprocessing techniques and understand how to handle missing values in a dataset for machine learning.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Dataset
Titanic Dataset (public dataset).

## Tasks Performed
1. Loaded the Titanic dataset.
2. Identified missing values using `isnull()`.
3. Analysed missing value counts and percentages.
4. Visualized missing values using Matplotlib.
5. Filled missing Age and Fare values using median.
6. Filled missing Embarked values using mode.
7. Dropped the Cabin column because it contained many missing values.
8. Removed remaining incomplete rows.
9. Exported the cleaned dataset as a CSV file.

## Missing Value Treatment
- **Median:** Used for numerical columns such as Age and Fare because median is less affected by outliers.
- **Mode:** Used for the categorical Embarked column because it replaces missing values with the most frequent category.
- **Drop Column:** Cabin was removed due to a high percentage of missing values.

## Deliverables
- Original missing value analysis
- Cleaned Titanic dataset
- Explanation of missing value treatment
- Data visualization

## Output
The cleaned dataset is saved as `cleaned_titanic.csv`.

## Conclusion
Successfully identified and handled missing values in the Titanic dataset using Pandas. This project helped me understand essential data preprocessing techniques used in machine learning.

## Author
AI & ML Intern
