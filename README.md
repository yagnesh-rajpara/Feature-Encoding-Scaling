# AI & ML Internship – Task 4  
## Feature Encoding & Scaling (Adult Income Dataset)

This repository contains the solution for **Task 4: Feature Encoding & Scaling** as part of the **AI & ML Internship**.  
The goal of this task is to perform **feature engineering** by encoding categorical variables and scaling numerical features to make the dataset machine-learning ready.

---

## 📌 Dataset Used
- **Adult Income Dataset (adult.csv)**  
  This dataset contains demographic and employment-related information used to predict whether a person earns more than $50K per year.

**Target Variable:**  
- `income` (<=50K, >50K)

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🎯 Task Objectives
- Identify categorical and numerical features  
- Apply **Label Encoding** where order exists  
- Apply **One-Hot Encoding** where no order exists  
- Scale numerical features using **StandardScaler**  
- Compare data before and after scaling  
- Explain the impact of scaling on ML algorithms  
- Save the preprocessed dataset  

---

## 📊 Work Performed
- Dataset inspection and feature classification  
- Handling missing values represented as `" ?"`  
- Label Encoding applied to the target variable (`income`)  
- One-Hot Encoding applied to nominal categorical features  
- Standardization of numerical features  
- Visualization of feature distribution before and after scaling  
- ML-readiness validation  

---

## 📁 Project Structure
```
📁 Task-4-Encoding-Scaling
│
├── AI_ML_Task4_Encoding_Scaling_Outstanding.ipynb
├── adult.csv
├── adult_income_processed.csv
└── README.md
```

---

## ▶️ How to Run
1. Clone the repository  
2. Ensure `adult.csv` is in the same directory as the notebook  
3. Open `AI_ML_Task4_Encoding_Scaling_Outstanding.ipynb`  
4. Run all cells from top to bottom  

After execution, the processed dataset `adult_income_processed.csv` will be generated.

---

## ✅ Outcome
- All features converted into numerical format  
- Numerical features standardized (mean = 0, std = 1)  
- Dataset fully prepared for machine learning algorithms  

---

## 🧠 Key Learnings
- Difference between Label Encoding and One-Hot Encoding  
- Importance of feature scaling  
- Impact of scaling on distance-based algorithms  
- Practical understanding of feature engineering  

---

**Author:** Internship Candidate  
