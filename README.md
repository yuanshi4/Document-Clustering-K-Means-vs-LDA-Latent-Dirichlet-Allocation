# Document-Clustering-K-Means-vs-LDA-Latent-Dirichlet-Allocation

### NLP Text Data Research

### Motivation
Text data has been a recent challenge for data scientists to research and analyze given its unstructured format and non-numeric feature. It is quite different from the typical numeric or categorical features we encounter more often in data analysis task. The dataset we picked is a merged data source from three data sources, because we want to ensure there are three big topics, that are somewhat different, in order for our clustering algorithm to explore.

[Note]: Alought our dataset only contains two columns, it is confirmed by instructor that it is ok to use, because text data are usually harder to clean and will eventual result in more columns.


- Kaggle Wine Review (400rows): Containing review written by professional sommelier about wines

- Kaggle Coronavirus_Tweet (400rows): Containing real posts from Twitter by real human users discussing coronavirus

- Kaggle Disater Tweet(400rows): Containing real posts from Twitter by real human users discussing disasters


### Algorithm Motivation
The intial motivation of this analysis is to evaluate

- A topic modeling(text clustering) algorithm's performance (like Latent Dirichlet Allocation(LDA))

- Compare with more ordinal clustering algorithm like Kmeans
We are interested to see what additional information we can gain from LDA, which is a algorithm designed for topic exploration

### Resource References
Miglani, Aman. “Coronavirus Tweets NLP - Text Classification.” Kaggle, 8 Sept. 2020, www.kaggle.com/datatattle/covid-19-nlp-text-classification.

Zackthoutt. “Wine Reviews.” Kaggle, 27 Nov. 2017,Kaggle, www.kaggle.com/zynicide/wine-reviews.

“Natural Language Processing with Disaster Tweets.” Kaggle, www.kaggle.com/c/nlp-getting-started/data.

Blei, David M., et al. “Latent Dirichlet Allocation.” Journal of Machine Learning Research, 1 Jan. 2003, https://jmlr.org/papers/volume3/blei03a/blei03a.pdf.
