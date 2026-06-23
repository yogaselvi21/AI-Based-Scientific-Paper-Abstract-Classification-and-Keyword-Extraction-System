# AI-Based Scientific Paper Abstract Classification and Keyword Extraction System

An intelligent AI system designed to automatically classify research papers, extract technical keywords, and provide explainable insights from scientific titles and abstracts. 

## 📌 Project Overview
Scientific research platforms receive thousands of papers daily. Manual classification is highly inefficient due to technical jargon, overlapping disciplines, and interdisciplinary content. 

This project automates the process by analyzing titles and abstracts to perform:
1. **Research Domain Classification:** Single-label assignment into primary domains.
2. **Multi-Label Topic Classification & Keyword and Keypharse Extraction:** Tagging papers that span multiple overlapping disciplines
3. **Keyword & Keyphrase Extraction:** Isolating critical terms.
4. **Explainable Classification:** Highlighting the exact terms that influenced the classification models.
5. **Streamlit Deployment:** A fully interactive frontend accessiblity.

---

## 🛠️ Tech Stack & Architecture
- **Language:** Python
- **Machine Learning & NLP:** Scikit-learn, Transformers, Spacy, NLTK
- **Frontend App:** Streamlit

---

## 📁 Repository Structure & Workflow
The project is divided into modular Jupyter Notebooks tracking the end-to-end ML pipeline:

1. 📓 **`Final_Project_Data_Cleaning_&_Preprocessing.ipynb`**
   - Text cleaning, tokenization, lemmatization, and stop-word removal.
   - Text vectorization and exploratory data analysis (EDA).

2. 📓 **`Final_Project_Research_Domain_Classification.ipynb`**
   - Building and evaluation of single-label classification models for primary research fields.

3. 📓 **`Final_Project_Multi-Label_Topic_Classification_&_Keyword_and_Key_phrase_Extraction.ipynb`**
   - Training multi-label classifiers to handle interdisciplinary papers belonging to multiple subjects simultaneously.
   - Developing features for extracting and isolating critical technical keyphrases.

4. 📓 **`Final_Project_Streamlit.ipynb`**
   - Prototyping the interactive user interface, keyword extraction algorithms, and explainability features.

---

## 📊 Expected Outcomes
- **Precision & Recall:** High classification metrics across highly technical, overlapping categories.
- **Interpretability:** Graphical or text-highlighted explanations showing *why* a model classified a paper into a specific domain.
