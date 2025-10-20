# 🎗️ Breast Cancer Classification using Artificial Neural Network (ANN)

A deep learning project that uses an **Artificial Neural Network (ANN)** to classify breast tumors as **benign** or **malignant** based on diagnostic features.  
This project demonstrates the use of neural networks in healthcare for early cancer detection with high accuracy and reliability.

---

## 🔍 Overview
- Load the **Breast Cancer Wisconsin (Diagnostic)** dataset.  
- Normalize features to ensure balanced gradient updates.  
- Build an ANN model with multiple dense layers and dropout regularization.  
- Train, evaluate, and visualize model performance.  
- Measure accuracy, confusion matrix, and ROC-AUC metrics.  

---

## 🧠 Model Architecture
| Layer | Type | Activation | Output |
|-------|------|-------------|--------|
| 1 | Dense (32) | ReLU | Hidden |
| 2 | Dropout (0.2) | — | — |
| 3 | Dense (16) | ReLU | Hidden |
| 4 | Dropout (0.1) | — | — |
| 5 | Dense (1) | Sigmoid | Output (binary) |

> Optimizer: **Adam**, Loss: **Binary Crossentropy**, Metric: **Accuracy**

---

## 🗂 Dataset
Dataset Source: **Breast Cancer Wisconsin (Diagnostic)**  
Available via `sklearn.datasets.load_breast_cancer()`

**Features include:**  
- Mean radius, texture, perimeter, area, smoothness, concavity, etc.  
- **Target:** 0 → *Malignant*, 1 → *Benign*

---

## 📈 Results
| Metric | Value (approx.) |
|---------|-----------------|
| Accuracy | 97–99% |
| ROC‑AUC | > 0.98 |
| Loss | Stable after 25 epochs |

**Key findings:**
- The ANN achieved high classification accuracy and low validation loss.  
- Overfitting was controlled using dropout layers.  
- Visualization of learning curves and ROC confirms generalization.

---

## ▶️ How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/ziaee-mohammad/Breast-Cancer-Classification-ANN.git
   ```
2. Open the notebook:  
   ```bash
   jupyter notebook model_ann_breast_cancer.ipynb
   ```
3. Run all cells to train and evaluate the model.  

---

## 🗃 Repository Structure
```
Breast-Cancer-Classification-ANN/
├─ model_ann_breast_cancer.ipynb    # main ANN notebook
├─ outputs/                         # optional - charts, metrics, saved models
└─ README.md
```

---

## 📊 Key Insights
- Neural networks can accurately classify tumors from tabular medical data.  
- Dropout and normalization significantly improve generalization.  
- The model provides a foundation for deep learning in medical diagnosis tasks.

---

## 📜 License
MIT — free to use with attribution.

---

## 👤 Author
**Mohammad Ziaee** — Computer Engineer | Data & AI Enthusiast  
📧 moha2012zia@gmail.com  
🔗 [GitHub Profile](https://github.com/ziaee-mohammad)
👉 Instagram: [@ziaee_mohammad](https://www.instagram.com/ziaee_mohammad/)


