# StudyHour-GPA-Regression


# Context
Dataset ini merupakan data yang terdiri atas GPA dan jam belajar dari 193 mahasiswa sarjana yang mengambil mata kuliah "Introductory Statistics" di sebuah universitas swasta USA pada tahun 2012. Data frame ini terdiri dari 193 rows dan 2 columns.

**Columns**
1. gpa: Grade Pint Average (GPA) of student. Range GPA pada data frame ini adalah 3.10-4.00
2. study_hours: Number of hours students study per week.

# Find Anomalies
1. Check Missing Values
2. Check duplicate rows based on all columns
3. Check Dtypes
The dataset is clean and has no missing values


# Simple EDA (Exploratory Data Analysis)
1. Create BoxPlot
2. Create Scatter Plot

# Create Regression Model
Machine Learning:
memprediksi GPA berdasarkan study hours mahasiswa. Apakah jam belajar mahasiswa memiliki dampak yang signifikan terhadap GPAnya?

Answer:
1.  R-squared: Total 0.018% jam belajar memengaruhi GPA mahasiswa
2. Prob (F-statistic): 0.0652
Lebih besar dari 0,05 sehingga terima H0 (tidak signifikan)

# Conclusion
Berdasarkan dataset ini, jam belajar mahasiswa tidak memengaruhi GPA mahasiswa. Hal tersebut dilihat melalui F-Statistic yang termasuk ke dalam H0 (tidak signifikan). Oleh karena itu, diperlukan model lain selain Linear Regression untuk memprediksi machine learning pada data frame ini. 
