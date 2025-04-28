BRFSS Heart Disease and Diabetes Prediction
📋 Project Overview
This project focuses on building predictive models to detect the risk of heart disease and diabetes based on health behavior data from the Behavioral Risk Factor Surveillance System (BRFSS) collected by the Centers for Disease Control and Prevention (CDC).

By leveraging machine learning models and analyzing key health-related factors, the goal is to support early identification of high-risk individuals and improve preventive healthcare strategies, especially in resource-limited settings.

📚 Dataset
Source: CDC BRFSS (Behavioral Risk Factor Surveillance System)

Years used: 2011, 2013, 2015

Format: CSV files (converted from SAS format using Python)

Key Features:

Demographic attributes (age, sex, education, income)

Health behaviors (alcohol consumption, smoking, physical activity)

Chronic health conditions (high blood pressure, high cholesterol, stroke)

⚙️ Data Preparation
Data Cleaning:

Removed inconsistent and missing responses.

Standardized feature values (e.g., binary encoding for yes/no).

Feature Engineering:

Created new fields like Heart Disease or Attack and Heavy Drinker based on multiple variables.

Combining Datasets:

Merged data from different years into a single dataset.

Feature Selection:

Selected 24 key independent variables relevant to heart disease and diabetes prediction.

Target Variables:

HeartDiseaseOrAttack

Diabetes

📈 Exploratory Data Analysis
Scatterplots: Relationship between age groups and heart disease incidence.

Histograms: Prevalence of heart disease across age brackets.

Pie Charts: Distribution of male and female participants.

🛠️ Models Used
Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Best Performance:

Random Forest achieved the highest accuracy of 90.3%.

🔥 Key Findings
Behavioral factors like alcohol consumption, physical activity, mental health, and healthcare access are strong predictors.

Random Forest model performed best, followed by Logistic Regression.

Machine learning models can aid healthcare providers in predicting chronic illnesses even when detailed medical tests are unavailable.

