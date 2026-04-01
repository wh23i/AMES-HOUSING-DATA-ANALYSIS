Ames Housing Project

This project is my capstone work for the ML Foundations course. I used the Ames Housing dataset to go through the main steps of a data analysis project from start to finish.

What I did

The project was divided into 4 phases:

Phase 1 – Cleaning
In this phase, I loaded the dataset, explored it, and cleaned it.  
I checked the data types, missing values, duplicates, and outliers.  
At the end, I created a `clean_data()` function so I could reuse the same cleaning steps later.

Phase 2 – Feature Engineering
In this phase, I worked on feature engineering.  
I converted some categorical columns into numeric values, applied ordinal encoding, and scaled some numerical columns.  
I also created new features such as ratios and interaction features, applied log transformation, used binning, and removed highly correlated columns.

Phase 3 – EDA
In this phase, I explored the data visually using different charts.  
I created histograms, boxplots, a heatmap, a scatter plot, and a groupby summary to understand the relationships between the variables, especially the ones connected to `SalePrice`.

Phase 4 – Math
In this phase, I applied a few basic math concepts to the dataset.  
I calculated the mean and standard deviation manually using NumPy, standardised one column by hand and compared it with `StandardScaler`, calculated cosine similarity, and estimated a simple probability from the data.

Files
- `01_cleaning.ipynb`
- `02_features.ipynb`
- `03_eda.ipynb`
- `04_math.ipynb`

Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
