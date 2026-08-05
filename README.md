# Students' Adaptability Level Prediction in Online Education Using Machine Learning

An end-to-end Machine Learning project that predicts students' adaptability to online education using demographic, technological, and socio-economic factors. This project applies exploratory data analysis, feature engineering, multiple machine learning algorithms, and explainable AI techniques (SHAP) to identify the key factors influencing student adaptability.

---

## Project Overview

The rapid adoption of online learning has highlighted significant differences in how students adapt to digital education. Factors such as internet connectivity, financial condition, device availability, and educational background can greatly impact students' learning experiences.

This project aims to:

- Predict students' adaptability to online education.
- Identify the most influential factors affecting adaptability.
- Compare multiple machine learning models.
- Improve model interpretability using Explainable AI (SHAP).
- Enhance model robustness through feature engineering and evaluation techniques.

---

## Research Questions

- Which demographic, technological, and socio-economic factors most significantly influence students' adaptability to online education?
- What is the relative importance of each factor?
- Which students are at higher risk of poor adaptability?

---

## Dataset

**Dataset:** Students' Adaptability Level in Online Education

**Source:** Kaggle

https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education

### Features

- Gender
- Age
- Education Level
- Institution Type
- IT Student
- Location
- Load Shedding
- Financial Condition
- Internet Type
- Network Type
- Class Duration
- Self LMS
- Device
- Adaptability Level (Target Variable)

---

#  Project Workflow

```text
Dataset
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Data Preprocessing
   │
   ▼
Feature Engineering
   │
   ▼
Machine Learning Models
   │
   ▼
Model Evaluation
   │
   ▼
SHAP Explainability
   │
   ▼
Methodology Improvements
```

---

#  Exploratory Data Analysis

The dataset was analyzed using multiple visualization techniques to understand feature distributions and relationships.

Visualizations included:

- Count Plots
- Bar Charts
- Pie Charts
- Heatmaps
- Distribution Analysis

### Key Insights

- Students with stable internet access demonstrated higher adaptability.
- Financial condition strongly influenced adaptability.
- Device type impacted learning experience.
- Load shedding negatively affected online learning.

---

#  Data Preprocessing

The following preprocessing steps were performed:

- Missing value handling
- Label Encoding
- Removal of irrelevant attributes
- Dataset cleaning
- Data balancing analysis

---

# Feature Engineering

Several new features were created to improve prediction performance.

| Feature | Description |
|----------|-------------|
| tech_access_score | Represents access to technology and internet |
| infra_difficulty | Measures infrastructure-related challenges |
| socioeconomic_score | Represents financial and socio-economic conditions |
| student_cluster | Student groups generated using K-Means clustering |

---

#  Machine Learning Models

The following classification models were implemented and compared:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression
- Naive Bayes
- LightGBM

---

#  Results

| Model | Accuracy |
|--------|----------|
|  Decision Tree | **92.8%** |
|  Random Forest | **92.0%** |
|  SVM | **77.9%** |
|  Logistic Regression | **63.5%** |
|  Naive Bayes | **60.3%** |

---

#  Explainable AI

SHAP (SHapley Additive exPlanations) was used to interpret the predictions of the trained models.

The analysis revealed that the following features had the greatest impact on adaptability:

- Internet Type
- Financial Condition
- Device
- Network Type
- Infrastructure Conditions

---

#  Methodology Improvements

To improve the baseline methodology, the following enhancements were introduced:

-  Feature Engineering
-  K-Means Clustering
-  SHAP Explainability
-  Cross Validation
-  LightGBM Comparison
-  Overfitting Analysis

These improvements increased the reliability and interpretability of the proposed machine learning pipeline.

---

#  Key Findings

- Technological resources are among the strongest predictors of adaptability.
- Financial condition significantly affects students' online learning experiences.
- Tree-based machine learning models outperform linear models for this dataset.
- SHAP provides meaningful explanations for model predictions.
- Feature engineering improves overall model understanding.

---

#  Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- SHAP
- Imbalanced-learn
- Yellowbrick

### Development Environment

- Kaggle Notebooks

---

#  References

1. https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0307221

2. https://www.mdpi.com/2078-2489/15/5/277

3. https://www.frontiersin.org/articles/10.3389/feduc.2025.1522905/full

4. https://www.researchgate.net/publication/370970932_Role_of_Artificial_Intelligence_in_Online_Education_A_Systematic_Mapping_Study

5. https://www.mdpi.com/2076-3417/14/12/5141

---

#  Author

**Zoha Waqas**

Computer Science Student | Machine Learning Enthusiast | Full Stack Developer

---

##  If you found this project interesting, consider giving it a star!
