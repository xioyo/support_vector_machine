# Support Vector Machines (SVM) Classification

## Objective
Implement Support Vector Machines to classify tumors in the Breast Cancer dataset and compare performance across different kernels, while tuning hyperparameters for optimal accuracy.

## Dataset
**Breast Cancer Wisconsin Dataset**  
Source: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
Target variable: `diagnosis` (M = Malignant, B = Benign)  

## Workflow
1. **Load & Inspect Data** – Read CSV, check shape, column names, and missing values.
2. **Preprocessing** – Drop `id`, encode `diagnosis` to numeric, scale features with `StandardScaler`.
3. **Train-Test Split** – 80% training, 20% testing.
4. **Train Models**  
   - SVM with **Linear kernel**  
   - SVM with **RBF kernel**  
5. **Evaluation** – Accuracy, precision, recall, F1-score, confusion matrix.
6. **Hyperparameter Tuning** – GridSearchCV to find best `C` and `gamma`.
7. **Cross-Validation** – 5-fold CV for reliable accuracy estimates.
8. **Visualization** – Plot decision boundaries using two selected features.

## Key Learnings
- Linear SVM is simpler but may underfit complex data.
- RBF kernel can adapt to more complex decision boundaries.
- Proper feature scaling is critical for SVM performance.
- Hyperparameter tuning greatly impacts results.

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

---
