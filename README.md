# 🧮 Principal Component Analysis (PCA) — Dimensionality Reduction & Clustering

This project demonstrates how **Principal Component Analysis (PCA)** can be used to reduce dataset dimensionality while retaining most of the variance.  
We also compare **K-Means clustering performance** before and after PCA using the **Wine dataset**.

---

## 🧩 Project Overview
- Load and preprocess the dataset  
- Visualize distributions and correlations  
- Perform PCA for dimensionality reduction  
- Evaluate explained variance  
- Apply K-Means clustering on:
  1. Original data  
  2. PCA-transformed data  
- Compare performance using **Silhouette Score** and **Davies–Bouldin Index**

---

## 📊 Technologies Used
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (PCA, K-Means, Metrics)  

---

## 🧠 Key Highlights
✔ Achieved 95% variance retention with fewer components  
✔ Improved clustering efficiency after dimensionality reduction  
✔ Visualized clean cluster separation in PCA-reduced space  
✔ Demonstrated trade-offs between variance retention and interpretability  

---

## ⚙️ How to Run
```bash
pip install -r requirements.txt
python PCA.ipynb
