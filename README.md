## Lab 3 README

### What are the ten most frequent words?
1. and: 713
2. the: 680
3. i: 585
4. to: 541
5. a: 468
6. of: 401
7. my: 360
8. that: 347
9. is: 344
10. in: 319

### What are the ten least frequent words?
As count size decreases, words with the same counts tend to increase (more words share the same rank). Therefore the ten least frequent words are actually a tie for a large number of words that all occur only once in the text.

### Comment on what this might mean.
A quick Google search reveals that the top ten words in Romeo and Juliet are also the top ten words in the English language, which suggests that simple articles, prepositions, and verbs in English haven't evolved much in the last 5 centuries or so. In fact, the frequency of words in all languages, both modern and ancient, have been observed to follow Zipf's law: the frequency of the word is the reciprocal of its rank (2nd most used word occurs about half as often as the 1st, the 3rd a third as often as the first, etc.) Strangely, the top ten words in Romeo and Juliet do NOT follow Zipf's law: 680/713 = 0.95, 585/713 = 0.82, 541/713 = 0.76, etc.

### BONUS: What does the plot of log[word count] vs. log[word rank] look like? Can you try to interpret this?
Like mentioned above, words that follow a power law will result in a linear relationship when plotting frequency or count versus rank on a log-log plot. The log-log plot generated for the words in Romeo and Juliet is on the border of being considered linear, which demonstrates that they don't closely follow a power law distribution (don't follow Zipf's law.)
