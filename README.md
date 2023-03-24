# Text Confirmation Dector

**"Are you sure you want to send that message?"**

A brief nlp classification tutorial. In this setting, we are creating a model that would decide when to display a confimation message to a user sending a message. Ideally we would like the model to detect messages that contain potentailly harmful or personal messages.

Positive Example: 
>input: 'I hate this job.' 
>
>Model's expected output: 1. 
>
>Decision: DISPLAY confirmation message to user.

Negative Example: 
>input: 'Good luck with the presentation today!' 
>
>Model's expected output: 0. 
>
>Decision: DO NOT DISPLAY confirmation message to user.

Positive Class WordCloud   |  Negative Class WordCloud
:-------------------------:|:-------------------------:
![](possent_cloud.png)  |  ![](negsent_cloud.png)

$P(y|x_1, ..., x_n) = \frac{P(y)P(x_1, ..., x_n|y)}{P(x_1, ..., x_n)}$ 


## Data gathering w/ChatGTP

![](DatasetCreationExample.png)

## Classification Methods

*Naive Bayes*

*Random Forest with TF-IDF and Text Embeddings*

## Limitations & Next Steps

