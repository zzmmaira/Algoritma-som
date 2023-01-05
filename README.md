---
title: "My document"
date: "`r Sys.Date()`"
author: Deden Istiawan-Institut Teknologi Statistika dan Bisnis Muhammadiyah
output:
  rmdformats::readthedown:
    self_contained: true
    thumbnails: true
    lightbox: true
    gallery: false
    highlight: tango
bibliography: references.bib
---

```{=html}
<style>
body{
text-align: justify}
</style>
```
```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents [@deCarvalho2012]. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

# Referensi