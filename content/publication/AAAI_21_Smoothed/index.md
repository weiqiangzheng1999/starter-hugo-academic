---
title: "The Smoothed Complexity of Computing Kemeny and Slater Rankings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lirong Xia
- Weiqiang Zheng

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-1-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 35th AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2021*

abstract: The computational complexity of winner determination under common voting rules is a classical and fundamental topic in the field of computational social choice. Previous work has established the NP-hardness of winner determination under some commonly-studied voting rules, such as the Kemeny rule and the Slater rule. In a recent position paper, \citet{Baumeister2020:Towards} questioned the relevance of  the worst-case nature of NP-hardness in social choice and proposed to conduct smoothed complexity analysis~\cite{Spielman2009:Smoothed} under~\cites{Blaser2015:Smoothed} framework.

In this paper, we develop the first smoothed complexity results for winner determination in voting.  We prove the smoothed hardness of Kemeny and Slater using the classical smoothed runtime analysis, and prove a parameterized typical-case smoothed easiness result for Kemeny. We also make an attempt of applying~\cites{Blaser2015:Smoothed}  smoothed complexity framework  in social choice contexts by proving that the framework categorizes an always-exponential-time brute force search algorithm as being smoothed poly-time, under a natural noise model based on the well-studied Mallows model in social choice and statistics. Overall, our results show that smoothed complexity analysis in computational social choice is a challenging and fruitful topic.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_arxiv: 'https://arxiv.org/abs/2010.13020'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
