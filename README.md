# 🔮 Next Word Prediction using LSTM (Shakespeare Hamlet)
## 📌 Project Overview
This project is a **Next Word Prediction system** built using **LSTM (Long Short-Term Memory)** neural networks.
👉 The model is trained on the **Shakespeare Hamlet dataset** to predict the next word in a sentence.
Example:
```text
Input: "to be or not to"
Output: "be"
```
🚀 Quick Start

### 1. Create Virtual Environment
python -m venv venv

### 2. Activate Virtual Environment

venv\Scripts\activate   # Windows
# OR
source venv/bin/activate   # Mac/Linux

### 3. Install Requirements
pip install -r requirements.txt

### 4. Run the Streamlit App
streamlit run app.py

## 🧠 Model Used

* Recurrent Neural Network (RNN)
* LSTM (Long Short-Term Memory)
* Embedding Layer for word representation

## ⚙️ Steps Followed (Training Pipeline)

### 📓 Notebook Workflow

1. Load dataset
2. Text preprocessing & tokenization
3. Create input sequences
4. Apply padding (same sequence length)
5. Split into features (X) and labels (y)
6. Train-test split (X_train, X_test, y_train, y_test)
7. Build LSTM model
8. Compile model
9. Train model
10. Evaluate accuracy
11. Test with new input sentences
12. Save trained model & tokenizer

## 🌐 Streamlit App (app.py)

The app performs:

* Loads trained **model (.h5)**
* Loads **tokenizer (.pickle)**
* Takes user input sentence
* Preprocesses input
* Predicts next word using LSTM
* Displays result interactively

## 📂 Project Structure
project/
│── app.py
│── model.h5
│── tokenizer.pickle
│── requirements.txt
│── notebook.ipynb
│── README.md


## 🎯 Key Features

* Real-time next word prediction
* Simple UI using Streamlit
* Deep learning-based NLP model
* Works on Shakespeare dataset

## 🧩 Tech Stack
* Python
* TensorFlow / Keras
* NumPy, Pandas
* Streamlit

## 📌 Future Improvements
* Use larger dataset
* Improve accuracy with GRU/Transformer
* Add sentence generation (not just next word)
* Deploy with faster model (ONNX / Torch)

## 🎯 Conclusion
This project demonstrates how **LSTM can understand sequence patterns** and predict the next word based on context.


💡 Built for learning Deep Learning + NLP concepts
