# 🧠 Mini Data Science Portfolio – Titanic Survival Prediction

This mini portfolio demonstrates a simple machine learning project using the Titanic dataset to predict passenger survival based on gender and age.

## 📊 Dataset Overview

The dataset contains the following relevant columns:
- `survived`: Whether the passenger survived (1) or not (0)
- `sex`: Gender of the passenger (male/female)
- `age`: Age of the passenger

## 🧼 Data Preparation

- Missing values in `sex` and `age` columns were removed
- The `sex` column was converted to numerical format:
  - `male` → 0
  - `female` → 1

## 🧠 Model Used

We used **Support Vector Machine (SVM)** with a linear kernel to build a classification model.

### Steps:
1. Load and clean the data
2. Convert categorical values
3. Split data into training and test sets (80/20)
4. Train the SVM model
5. Evaluate with accuracy and classification report
6. Make a prediction on a sample input

## 🧪 Sample Prediction

The model was tested to predict survival for a sample input:
```python
sex = 1 (female)
age = 30

