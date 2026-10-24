

# 🩺 Breast Cancer Classification Using Deep Learning

<p align="center">

### 🤖 Neural Networks • Binary Classification • Model Optimization

</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12%2B-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?style=for-the-badge&logo=keras)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---
<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/104e5330-c598-4ad9-a805-a280ba84bc7e" />





## 🏷️ Skills Badges

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-00599C?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-8A2BE2?style=for-the-badge)
![Neural Networks](https://img.shields.io/badge/Neural%20Networks-007ACC?style=for-the-badge)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

![Binary Classification](https://img.shields.io/badge/Binary%20Classification-2E8B57?style=for-the-badge)
![Early Stopping](https://img.shields.io/badge/Early%20Stopping-4682B4?style=for-the-badge)
![Dropout](https://img.shields.io/badge/Dropout-Regularization-9370DB?style=for-the-badge)
![L1%20%2F%20L2](https://img.shields.io/badge/L1%20%2F%20L2-Regularization-FF6347?style=for-the-badge)

</p>



## 📌 Project Overview

🧠 This project develops and evaluates **Deep Learning models** for 🩺 **Breast Cancer Classification** using the Breast Cancer Wisconsin dataset available through Scikit-learn.

🎯 The main objective is to classify breast tumors into two categories:

- 🔴 **Malignant (Cancerous)**
- 🟢 **Benign (Non-cancerous)**

📊 The classification is performed using **30 numerical input features** to help identify patterns in tumor measurements.

🤖 The project explores the following Deep Learning techniques:

- 🧠 **Single-Layer Perceptron (SLP)**
- 🏗️ **Multi-Layer Perceptron (MLP)**
- ⚡ **Activation Functions** (ReLU, Tanh)
- ⏹️ **Early Stopping**
- 🎲 **Dropout Regularization**
- 🛡️ **L1, L2, and L1-L2 Regularization**

📈 Different neural network configurations are evaluated to compare their performance and understand how training and regularization techniques can improve model generalization.


## 🎯 Project Objectives

- 📂 **Dataset Loading:** Load and understand the Breast Cancer Wisconsin dataset.
- 🔍 **Exploratory Data Analysis (EDA):** Explore data patterns, distributions, and feature relationships.
- 🧹 **Data Validation:** Validate the dataset and inspect the distribution of target classes.
- 🔥 **Correlation Analysis:** Analyze correlations between numerical input features.
- ✂️ **Train-Test Splitting:** Split the dataset into training and testing sets.
- 📏 **Feature Scaling:** Apply `StandardScaler` to numerical features.
- 🧠 **Baseline Model:** Build a Single-Layer Perceptron (SLP) for baseline classification.
- 🏗️ **Deep Learning Model:** Develop a Multi-Layer Perceptron (MLP) using ReLU and Tanh activation functions.
- ⏹️ **Early Stopping:** Monitor validation loss and stop training when improvement stalls.
- 🎲 **Dropout Regularization:** Experiment with dropout rates to help reduce overfitting.
- 🛡️ **Weight Regularization:** Compare L1, L2, and combined L1-L2 regularization techniques.
- 📊 **Model Evaluation:** Evaluate and compare model performance using relevant classification metrics.
- 💡 **Medical AI Exploration:** Explore the potential of deep learning for medical diagnosis support.



## 🛠️ Technologies Used

| 💻 Technology | 🎯 Purpose |
|---|---|
| 🐍 **Python** | Programming and model development |
| 🐼 **Pandas** | Data handling and analysis |
| 🔢 **NumPy** | Numerical operations and array processing |
| 📊 **Matplotlib** | Visualizing training curves and model results |
| 🎨 **Seaborn** | Statistical data visualization |
| 🤖 **Scikit-learn** | Dataset loading, preprocessing, train-test splitting, and model evaluation |
| 🧠 **TensorFlow** | Deep learning model development |
| ⚙️ **Keras** | Neural network architecture, training, and optimization |
| 📓 **Jupyter Notebook** | Interactive coding, experimentation, and documentation |





### 🔬 Key Deep Learning Concepts

- 🧠 **Neural Networks:** SLP and MLP architectures
- ⚡ **Activation Functions:** ReLU and Tanh
- ⏹️ **Early Stopping:** Monitoring validation performance
- 🎲 **Dropout:** Reducing overfitting
- 🛡️ **Regularization:** L1, L2, and L1-L2
- 📈 **Model Evaluation:** Measuring classification performance




## 📂 Dataset Information

📊 This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** provided by `sklearn.datasets.load_breast_cancer`.

### 📋 Dataset Summary

| 🔹 Property | 📌 Details |
|---|---|
| 🏷️ **Dataset Name** | Breast Cancer Wisconsin (Diagnostic) |
| 📊 **Total Observations** | 569 |
| 🔢 **Total Input Features** | 30 |
| 🎯 **Target Classes** | 2 |
| 🔴 **Malignant Samples** | 212 |
| 🟢 **Benign Samples** | 357 |
| 🧪 **Training Samples** | 455 |
| 🧾 **Testing Samples** | 114 |
| 🤖 **Problem Type** | Binary Classification |

### 🎯 Target Classes

| 🏷️ Class | 🔬 Description | 🔢 Label |
|---|---|---:|
| 🔴 **Malignant** | Cancerous tumor | `0` |
| 🟢 **Benign** | Non-cancerous tumor | `1` |

📌 **Objective:** 🤖 Train a deep learning model to classify tumors into malignant and benign categories using numerical features from the Breast Cancer Wisconsin dataset.

### 🔬 Dataset Features

The Breast Cancer Wisconsin dataset contains **30 numerical features** extracted from digitized images of breast mass samples. These features describe the characteristics of cell nuclei and help the neural network identify patterns associated with malignant and benign tumors.



#### 📊 Key Features

- 📏 **Radius** — Measures the average distance from the center to points on the boundary.
- 🧵 **Texture** — Represents variations in grayscale intensity.
- 📐 **Perimeter** — Measures the boundary length of the cell nucleus.
- 🔢 **Area** — Represents the area of the cell nucleus.
- 💧 **Smoothness** — Measures local variations in radius lengths.
- 🧩 **Compactness** — Describes how compact the cell nucleus is.
- 🔍 **Concavity** — Measures the severity of concave portions of the boundary.
- ⚖️ **Symmetry** — Describes the symmetry of the cell nucleus.

📌 **Note:** The dataset includes additional measurements such as concave points, fractal dimension, and mean, standard error, and worst values for several features.

🎯 **Purpose:** These numerical measurements help the deep learning model learn patterns that support the classification of tumors into two target classes: **Malignant (0)** and **Benign (1)**.



### 🎯 Target Classes

- **Malignant (0):** Cancerous tumor.
- **Benign (1):** Non-cancerous tumor.

- 

### 📊 Input Features

The Breast Cancer Wisconsin dataset contains **30 numerical input features** extracted from digitized images of breast mass samples. These features help neural network models learn patterns and classify tumors as malignant or benign.

#### 🔍 Key Input Features

- 📏 **Mean Radius** — Average radius of the cell nucleus.
- 🧵 **Mean Texture** — Average variation in grayscale intensity.
- 📐 **Mean Perimeter** — Average boundary length.
- 🔢 **Mean Area** — Average area of the cell nucleus.
- 💧 **Mean Smoothness** — Measures local variations in radius lengths.
- 🧩 **Mean Compactness** — Describes the compactness of the cell nucleus.
- 🔬 **Mean Concavity** — Measures the severity of concave portions.
- ⚖️ **Mean Symmetry** — Measures the symmetry of the cell nucleus.
- 📈 **Worst-Case Measurements** — Represent the largest or most extreme feature values.
- 📊 **Standard-Error Measurements** — Describe the variability of feature measurements.

🧠 **Model Input:** All 30 numerical features are used as input variables for the neural network models.



🎯 **Goal:** Learn patterns from these measurements to classify tumors into **Malignant (0)** and **Benign (1)** categories.

## ⚙️ Project Workflow

This project follows an **end-to-end deep learning workflow** to classify breast tumors using the Breast Cancer Wisconsin dataset.

### 🔄 Step-by-Step Workflow

1. 📥 **Data Loading:** Load the dataset using Scikit-learn.
2. ✅ **Data Validation:** Check the dataset shape, feature columns, and target class distribution.
3. 📊 **Exploratory Data Analysis (EDA):** Visualize class distribution and feature correlations.
4. ✂️ **Train-Test Split:** Split the dataset into 80% training and 20% testing data using stratification and `random_state=42`.
5. 📏 **Feature Scaling:** Apply `StandardScaler`, fitting it only on the training data to prevent data leakage.
6. 🧪 **Baseline Model (SLP):** Build and evaluate a Single-Layer Perceptron as the baseline model.
7. 🧠 **Deep Learning Model (MLP):** Build a Multi-Layer Perceptron with hidden layers and activation functions.
8. 🛑 **Early Stopping:** Monitor validation loss and stop training when improvement stalls.
9. 💧 **Dropout Regularization:** Experiment with different dropout rates to help reduce overfitting.
10. ⚖️ **L1, L2, and L1-L2 Regularization:** Compare different regularization techniques to control model complexity.
11. 📈 **Model Evaluation:** Compare test accuracy, precision, recall, F1-score, and confusion matrices where implemented.
12. 📝 **Final Analysis:** Summarize model performance, compare results, and discuss limitations.

### 🎯 Project Outcome

The workflow helps evaluate different neural network architectures and regularization techniques to understand their impact on classification performance.


## 🧠 Deep Learning Models Implemented

This project implements and compares different neural network architectures and regularization techniques for breast cancer classification using TensorFlow and Keras.

### 1. 🧪 Single-Layer Perceptron (SLP)

A baseline neural network model designed for binary classification.

- ⚙️ **Optimizer:** Adam
- 📉 **Loss Function:** Binary Cross-Entropy
- 📊 **Evaluation Metric:** Accuracy
- 🔄 **Training:** 50 epochs

### 2. 🧠 Multi-Layer Perceptron (MLP)

A neural network with hidden layers that learns complex, nonlinear relationships between input features and target classes.

- 🔗 **Architecture:** Hidden layers with ReLU activation
- 🔄 **Activation Comparison:** ReLU vs. Tanh
- ⚙️ **Optimizer:** Adam
- 📉 **Loss Function:** Binary Cross-Entropy

### 3. 🛑 Early Stopping

The `EarlyStopping` callback monitors validation loss and stops training when improvement stalls.

- 📊 **Monitored Metric:** `val_loss`
- 🎯 **Purpose:** Reduce unnecessary training and help control overfitting
- 🔄 **Benefit:** Can restore the best model weights when `restore_best_weights=True`

### 4. 💧 Dropout Regularization

Dropout randomly disables a proportion of neurons during training to help prevent overfitting.

**Dropout rates tested:**

- 🔹 `0.1` — 10% dropout
- 🔹 `0.3` — 30% dropout
- 🔹 `0.5` — 50% dropout

🎯 **Objective:** Compare how different dropout rates affect model performance.

### 5. ⚖️ L1, L2, and L1-L2 Regularization

Regularization adds penalties to model weights to help control model complexity.

- 🔹 **L1 Regularization:** Adds a penalty based on the absolute values of weights.
- 🔹 **L2 Regularization:** Adds a penalty based on the squared values of weights.
- 🔹 **L1-L2 Regularization (ElasticNet-style):** Combines L1 and L2 penalties.

📊 **Objective:** Compare the regularization techniques to understand their effects on model performance and overfitting.

### 🏆 Overall Goal

Evaluate the baseline and deeper neural network models, experiment with training techniques, and identify approaches that perform well on the test dataset.



## 📊 Model Results

The following test accuracy results are reported in the notebook. These results compare the performance of the baseline model, MLP architecture, and different regularization techniques.

| 🧠 Model / Configuration | 🎯 Test Accuracy |
|---|---:|
| 🧪 Single-Layer Perceptron (SLP) | **92.98%** |
| 🔗 MLP (ReLU) | **94.74%** |
| 💧 MLP with Dropout (`0.1`) | **95.61%** |
| ⚖️ MLP with L1 Regularization | **95.61%** |
| ⚖️ MLP with L2 Regularization | **95.61%** |
| 🔗 MLP with L1-L2 Regularization | **95.61%** |



### 🏆 Key Observations

- 📈 **Improved Performance:** The MLP with ReLU achieved higher test accuracy than the baseline SLP.
- 💧 **Dropout Regularization:** The MLP with a dropout rate of `0.1` achieved **95.61%** test accuracy.
- ⚖️ **Regularization Results:** The L1, L2, and L1-L2 regularized models each achieved **95.61%** test accuracy.
- 📊 **Comparable Performance:** Multiple model configurations achieved the same reported test accuracy.

📌 **Note:** These results are based on the values reported in the notebook. Test accuracy alone does not determine which model generalizes best. Additional metrics, such as precision, recall, F1-score, confusion matrices, and validation performance, can provide a more complete evaluation.



### 🏆 Key Findings

- 🧪 **Baseline Model:** The Single-Layer Perceptron (SLP) achieved **92.98%** test accuracy.
- 🧠 **MLP Performance:** The ReLU-based Multi-Layer Perceptron achieved **94.74%** test accuracy.
- 💧 **Dropout Technique:** The MLP with a dropout rate of `0.1` achieved **95.61%** test accuracy.
- ⚖️ **Regularization Results:** The L1, L2, and L1-L2 configurations each achieved **95.61%** test accuracy in the reported comparison.
- 📊 **Generalization:** High validation accuracy alone does not guarantee strong performance on unseen data.
- 🩺 **Medical Classification:** Malignant-class recall and false-negative counts are especially important alongside overall accuracy, as missed malignant cases are a critical concern.

📌 **Note:** These figures represent the individual configurations reported in the notebook. Equal test accuracy does not imply identical precision, recall, confusion matrices, or clinical usefulness.


## 📈 Visualizations

The notebook includes visualizations to explore the dataset, monitor neural network training, and compare model performance.

### 📸 Recommended Screenshots

| 🖼️ Screenshot | 📝 Description |
|---|---|
| `01_class_distribution.png` | 🔬 Malignant vs. benign class distribution |
| `02_correlation_heatmap.png` | 🌡️ Correlation between input features |
| `03_slp_training_curves.png` | 📉 SLP training and validation curves |
| `04_mlp_training_curves.png` | 🧠 MLP training and validation curves |
| `05_early_stopping.png` | 🛑 Early Stopping behavior |
| `06_dropout_comparison.png` | 💧 Comparison of dropout configurations |
| `07_regularization_comparison.png` | ⚖️ L1, L2, and L1-L2 comparison |
| `08_model_comparison.png` | 🏆 Model evaluation summary |

### 📂 Screenshot Directory Structure

Save your actual screenshots in the following folder structure:

```text
project/
├── README.md
├── Breast Cancer Wisconsin.ipynb
└── screenshots/
    ├── 01_class_distribution.png
    ├── 02_correlation_heatmap.png
    ├── 03_slp_training_curves.png
    ├── 04_mlp_training_curves.png
    ├── 05_early_stopping.png
    ├── 06_dropout_comparison.png
    ├── 07_regularization_comparison.png
    └── 08_model_comparison.png
```






### 📊 Class_distribution

<img width="690" height="490" alt="image" src="https://github.com/user-attachments/assets/26435722-ec86-4b19-a171-ee64f516dc0c" />





### 🔥 Correlation Heatmap

<img width="1472" height="1190" alt="image" src="https://github.com/user-attachments/assets/afd6c29f-09cf-4186-80e9-11111cea8235" />






### 📉 SLP Training Curves

<img width="1489" height="495" alt="image" src="https://github.com/user-attachments/assets/2d27f965-c91a-4084-88ef-d79b2435d32d" />








### 📈 MLP Training Curves

<img width="1790" height="495" alt="image" src="https://github.com/user-attachments/assets/b83e19b0-7ee8-4966-bdb1-b9403e18b76f" />





### ⏹️ Early Stopping

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/e671226d-4a23-42b6-903d-51c98a57ff1f" />






### 💧 Dropout Comparison

<img width="1790" height="495" alt="image" src="https://github.com/user-attachments/assets/b83e19b0-7ee8-4966-bdb1-b9403e18b76f" />






### 🛡️ Regularization Comparison

<img width="1789" height="495" alt="image" src="https://github.com/user-attachments/assets/dc2979e5-5e45-4da2-b6c8-d2c55c849d58" />




### 🏆 Model Comparison — Evaluate All Three Regularized Models

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/2ec295da-9b4a-4712-8c71-6d83a54218e9" />





📌 **Important:** Add only screenshots that you have actually generated and committed to your GitHub repository. Ensure the image filenames and folder paths match exactly.


## 📁 Project Structure

The repository follows a clean and organized structure to make the project easy to understand, execute, and maintain.

```text
Breast-Cancer-Classification/
│
├── 📄 README.md
├── 📓 Breast Cancer Wisconsin.ipynb
├── ⚙️ requirements.txt
│
└── 📂 screenshots/
    ├── 01_class_distribution.png
    ├── 02_correlation_heatmap.png
    ├── 03_slp_training_curves.png
    ├── 04_mlp_training_curves.png
    ├── 05_early_stopping.png
    ├── 06_dropout_comparison.png
    ├── 07_regularization_comparison.png
    └── 08_model_comparison.png
```

### 📌 File Descriptions

- 📄 **`README.md`** — Contains the project overview, objectives, workflow, model results, and documentation.
- 📓 **`Breast Cancer Wisconsin.ipynb`** — Jupyter Notebook containing data loading, EDA, preprocessing, neural network training, and model evaluation.
- ⚙️ **`requirements.txt`** — Lists the Python libraries required to run the project.
- 📂 **`screenshots/`** — Stores dataset visualizations, training curves, and model comparison plots.

💡 **Note:** Ensure the filenames and folder paths match your actual GitHub repository. Include only files and screenshots that have been saved and uploaded.

## 💻 Installation & Setup

Follow these steps to set up and run the Breast Cancer Classification project on your local machine.

### 📥 Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

🔗 Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 📂 Step 2: Navigate to the Project Folder

```bash
cd Breast-Cancer-Classification
```

### 📦 Step 3: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

📌 This command installs the Python libraries listed in `requirements.txt`.

### 🚀 Step 4: Launch Jupyter Notebook

```bash
python -m jupyter notebook
```

### 🧠 Step 5: Run the Notebook

1. Open `Breast Cancer Wisconsin.ipynb`.
2. Select the correct Python environment or kernel.
3. Run the notebook cells from top to bottom.
4. Review the visualizations, training results, and model evaluation metrics.

### ⚠️ Important Notes

- 🐍 **Python Version:** Use a Python version compatible with your installed TensorFlow release.
- 🧠 **TensorFlow/Keras:** Ensure TensorFlow is installed correctly before running the model-training cells.
- 📂 **File Paths:** Keep the notebook, `requirements.txt`, and screenshot folders in their expected locations.
- ✅ **Final Check:** Restart the kernel and run all cells to verify that the notebook executes without errors.

🎯 **Expected Outcome:** A successfully executed notebook containing data analysis, neural network experiments, and breast tumor classification results.


## 📦 Requirements

This project uses the following Python libraries for data analysis, visualization, and deep learning model development.

### 🛠️ Dependencies

| 📚 Library | 🎯 Purpose |
|---|---|
| 🧠 **TensorFlow** | Build and train neural network models |
| 🤖 **Scikit-learn** | Dataset loading, preprocessing, scaling, and evaluation |
| 🐼 **Pandas** | Data manipulation and analysis |
| 🔢 **NumPy** | Numerical computations |
| 📊 **Matplotlib** | Create charts and visualizations |
| 🎨 **Seaborn** | Statistical data visualization |
| 📓 **Jupyter Notebook** | Run and document experiments interactively |

### 📥 Install Dependencies

Install all required libraries using the following command:

```bash
python -m pip install -r requirements.txt
```

### ✅ Verify Installation

Check whether TensorFlow and Scikit-learn are installed correctly:

```python
import tensorflow as tf
import sklearn

print("TensorFlow version:", tf.__version__)
print("Scikit-learn version:", sklearn.__version__)
```

📌 **Note:** Make sure your Python version is compatible with the TensorFlow version specified in `requirements.txt`.

```
```
## 💡 Key Learnings

Through this project, I gained practical experience with fundamental deep learning concepts, neural network architectures, and model evaluation techniques.

### 🧠 Deep Learning Concepts

- 🎯 **Binary Classification** — Classifying tumors into malignant and benign categories.
- 🧪 **Single-Layer Perceptron (SLP)** — Building a baseline neural network.
- 🔗 **Multi-Layer Perceptron (MLP)** — Learning nonlinear relationships using hidden layers.
- ⚡ **Activation Functions** — Exploring ReLU and Tanh activation functions.
- ⚙️ **Adam Optimizer** — Updating model weights during training.
- 📉 **Binary Cross-Entropy** — Measuring prediction errors in binary classification.

### 📊 Data Analysis & Preprocessing

- 🔍 **Exploratory Data Analysis (EDA)** — Understanding class distributions and feature relationships.
- 📏 **Feature Scaling** — Standardizing numerical input features.
- 🛡️ **Data Leakage Prevention** — Fitting the scaler only on training data.
- 📈 **Training and Validation Curves** — Monitoring model learning and potential overfitting.

### 🛠️ Model Optimization & Evaluation

- 🛑 **Early Stopping** — Stopping training when validation performance stops improving.
- 💧 **Dropout Regularization** — Testing dropout rates to help reduce overfitting.
- ⚖️ **L1 and L2 Regularization** — Exploring penalties that control model complexity.
- 🏆 **Model Comparison** — Comparing test accuracy and other evaluation metrics where implemented.

### 🩺 Medical Classification Considerations

- 🔬 Understanding the importance of malignant-class recall.
- ⚠️ Recognizing the impact of false-negative predictions.
- 📋 Evaluating models using multiple metrics instead of accuracy alone.
- 💡 Understanding that a machine learning model is an educational tool and not a substitute for professional medical diagnosis.

### 🚀 Overall Learning Outcome

This project strengthened my practical understanding of **deep learning, neural network training, regularization, and medical classification evaluation** using Python and TensorFlow/Keras.



## 🚀 Future Improvements

Several enhancements can be explored to improve model performance, evaluation reliability, reproducibility, and practical usability.

### 🔬 Model Development & Evaluation

- 🧠 **Explore More Architectures** — Compare additional neural network architectures and configurations.
- 📊 **Comprehensive Evaluation** — Evaluate precision, recall, F1-score, ROC-AUC, and confusion matrices consistently across all models.
- 🔄 **Cross-Validation** — Use cross-validation for more robust performance estimates.
- 🎯 **Hyperparameter Tuning** — Systematically optimize learning rates, batch sizes, hidden layers, and regularization parameters.

### ⚙️ Reproducibility & Deployment

- 🎲 **Reproducible Experiments** — Set random seeds for data splitting, model initialization, and training where supported.
- 💾 **Model Saving** — Save the final trained model along with its fitted `StandardScaler`.
- 🌐 **Streamlit Application** — Develop an interactive demonstration app for exploring model predictions.

### 🔍 Interpretability & Validation

- 🧩 **Model Interpretability** — Explore feature importance methods or SHAP to better understand model predictions.
- 🧪 **Independent Validation** — Evaluate the workflow on independent data to assess generalization.
- 🩺 **Responsible Medical AI** — Investigate data quality, bias, and clinical validation requirements before considering any real-world medical application.

### 🎯 Long-Term Goal

Build a more reproducible, interpretable, and thoroughly evaluated deep learning workflow while recognizing that this educational project is **not a clinically validated diagnostic system**.



## ⚠️ Disclaimer

This project is intended for **educational and research purposes only**. It is not a certified medical diagnostic tool and must not be used to make real medical decisions.

🩺 Any potential clinical application would require independent validation, rigorous clinical evaluation, appropriate regulatory approval, and assessment by qualified medical professionals.

## 🏁 Conclusion

This project demonstrates an end-to-end **deep learning workflow for breast tumor classification** using the Breast Cancer Wisconsin dataset.

Throughout the project, the notebook explores baseline and multilayer neural networks, activation functions, Early Stopping, Dropout, and weight regularization.

📊 The reported experiments achieved test accuracies ranging from **92.98% to 95.61%** across the listed model configurations.

### 🎯 Project Highlights

- 🧠 Implemented and compared Single-Layer Perceptron (SLP) and Multi-Layer Perceptron (MLP) models.
- ⚙️ Explored ReLU and Tanh activation functions.
- 🛑 Practiced Early Stopping and Dropout to help control overfitting.
- ⚖️ Compared L1, L2, and L1-L2 regularization techniques.
- 📈 Evaluated model performance using reported test accuracy results.

💡 **Overall Learning Outcome:** This project provided practical experience in neural network development, model evaluation, and techniques for improving generalization.

🚀 **Future Goal:** Continue improving model reliability, interpretability, and reproducibility through comprehensive evaluation and independent validation.

📌 *This project is an educational demonstration and is not a clinically validated diagnostic system.*


## 👨‍💻 Author

**Rahul Zala**

💻 *Python Developer | Data Analytics | Machine Learning | Deep Learning*

📌 Passionate about exploring data, building machine learning models, and developing deep learning projects.

---

<p align="center">
  ⭐ If you find this project useful, please consider giving the repository a star!
  <br>
  🤝 Contributions, feedback, and suggestions are always welcome.
</p>
