# 📰 NLP_Bitcoin-News-Sentiment-Analysis
The goal of this project is to apply NLP techniques to extract sentiment from Bitcoin-related news content. The classified sentiment (positive, negative, neutral) can be used to observe patterns in market sentiment and investor psychology, potentially aiding in trading strategies or market analysis.

# 🚀 Features
🧹 Text Preprocessing  - Cleaned raw text (regex, tokenization, stopword removal, lemmatization) & Preserved domain-specific terminology in finance.

📋 Text Augmentation   - Data augmentation on imbalanced text dataset (Synonym Replacement using nlpaug).

📊 Visualization       - Plot word counts for each sentiment, chi2 test visualization and shows sentiment distribution.

🧠 Feature Extraction - Vectorized pre-processed text with BoW, ngram, TF-IDF and Word Embedding.

🤖 Sentiment Classification - Developed and trained machine learning models on the vectorized text to classify sentiment.

# 🧰 Tech Stack
**Programming Language**: Python

**Libraries/Tool**:

NLP - nltk, spaCy, TextBlob, nlpaug, transformers

Data - pandas, numPy

Visualization - matplotlib, seaborn

Machine Learning - scikit-learn

# 📊 Results
🔤 **Top Words Visualization**:

Top 20 words for negative sentiment after text cleaning.<br> Preserve stop words which are important in finance domain (eg. down, up, drop).

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/1444c0e8-ec28-408f-bf59-3d2e41218990" />


<br>🔝 **Features Selection by Chi-square Score**:

ML models overfitted with vectorized text data (BoW, ngram, TF-IDF).<br> Picked top features using Chi2 test to reduce feature's dimension.

<img width="829" height="470" alt="image" src="https://github.com/user-attachments/assets/3bb3cc8c-8ea0-403c-a406-30d600c8abd4" /><br>

📈 **Model Evaluation**:

Trained RF, NB and GB model for sentiment classification.<br>
Best model: NB<br>

Training accuracy: 74%<br>
Testing accuracy: 71%<br>

Feature selection overcame massive overfitting issue on ML models.<br>

Confusion Matrix:

<img width="629" height="505" alt="image" src="https://github.com/user-attachments/assets/3ff3aaa5-a7cf-4f6e-bdb8-c1c56e9f7fd3" />
<br>


