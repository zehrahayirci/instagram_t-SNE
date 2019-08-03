# Instagram_t-SNE
[t-SNE](https://lvdmaaten.github.io/tsne/) visualization of instagram posts

t-SNE is a popular dimension reduction algorithm. Why not try to use it on instagram posts!

This notebook best work in Google Colab, and don't forget to enable GPU from Edit -> Notebook Settings -> Hardware

I use [Jonker-Volgenant algorithm](https://blog.sourced.tech/post/lapjv/) to create a nice grid for instagram!

[My instagram](https://www.instagram.com/tokyoda100gun/) with Histogram t-SNE

<img alt="insta t-SNE" src="https://github.com/zehrahayirci/instagram_t-SNE/images/blob/master/insta_histogram.png" width="300">

1500 images of cats, dogs and bears using their histogram

<img alt="Histogram t-SNE" src="https://github.com/zehrahayirci/instagram_t-SNE/images/blob/master/histogram_tsne_3.png" width="500">


Using their pretrained ImageNet features

<img alt="Imagenet t-SNE" src="https://github.com/zehrahayirci/instagram_t-SNE/images/blob/master/tsne_features.png" width="500">


Using both histogram and pretrained fetures

<img alt="Both t-SNE" src="https://github.com/zehrahayirci/instagram_t-SNE/images/blob/master/tsne_all.png" width="500">

Read the [t-SNE pape](http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf), watch Van der Maaten's [Google Talk](https://www.youtube.com/watch?v=RJVL80Gg3lA) or check the examples on [his blog](https://lvdmaaten.github.io/tsne/)


Inspired from Prabodh Tripathi's [blog post](https://thebittheories.com/t-sne-visualization-of-instagram-posts-d5915ae99e63)

