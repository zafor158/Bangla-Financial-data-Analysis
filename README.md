# Bangla-Financial-data-Analysis

In today's society, information is power. It is impossible to manage life without data. Thus,
gathering data is a desire for the future. It is really hard to find Bangla datasets, especially
in Bangladesh. The fastest possible solution to this issue is required. If not, the world would
not be aware of our field of study. Here, we gathered Bangla financial data—context,
question, and response pairs—for our BanglaFinGPT. There are many segments in our
data collection including Tax, VAT, and Customs. We used the NBR website to get
financial statistics in Bangla. Initially, we collected data from the NBR website that
includes data about Finance, VAT, Tax and Customs. We created Question-Answer pairs
using GPT-3.5. Then, we collected the context from the resource file and applied to the
GPT-3.5 in order to create the Question-Answer pairs. Next, we instructed the GPT-3.5 to
produce at least 20 resembling Bangla Question-Answer pairs that addressed every aspect
of the context. After that we selected the most insightful and useful Q&A pairs after
producing. Furthermore, we also used Gemini to improvise the Q&A pairs. Finally, we
translated the Context and Q&A pairs to English. So, Bangla and English are the two
distinct groups in our data set.

![image](https://github.com/user-attachments/assets/e3e2ce1e-969b-43be-9b16-20e8ba0545f5)

# Dataset Collection

The source of our data is PDFs available on NBR website. We extracted specific sections
of text from these PDFs, focusing on relevant contexts. Using this content, we generated
several Question-Answer (Q&A) pairs with the help of AI models like GPT-3.5 and
Gemini AI. After generating a Q&A pair we translated into English language, so that we
will have multi-language support in our model which we will train using this Dataset.
We obtained several important findings from our dataset study. Context, Question, and
Answer are the three primary text columns in the dataset. The Context column is the most
diverse, with word counts ranging from 110 to 2319 and character counts from 766 to
13800, also has different contextual meanings based on the string. Even though the
Question-Answer columns were shorter, they still had a wide range of word counts, with
answers ranging from 5 to 610 and questions from 2 to 47. The Context column was more
important, with an average of 662 words and 4225 characters per context. The Answer
column had an average of 25 words and 156 characters, and the Question column had an
average of 13 words and 80 characters. Significant skewness and kurtosis values were also
found in the data, especially for the Answer column, which suggested a strongly skewed
and peaked distribution. Also, usual lengths for entries were highlighted, with the Context
typically being 373 words long, and the Question-Answer entries often having 10 and 21
words. These findings clearly understand the dataset's structure and distribution, setting
the stage for further analysis.

![image](https://github.com/user-attachments/assets/3cb14c5c-0119-4f0e-93af-91846f51545f)

