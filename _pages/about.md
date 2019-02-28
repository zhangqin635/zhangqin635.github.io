---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Xuesong Zhou joined the School of Sustainable Engineering and the Built Environment at Arizona State University in 2013. Previously, he was an associate professor at University of Utah.

Zhou’s research work focuses on dynamic traffic assignment, traffic estimation and prediction, large-scale routing and rail scheduling. He has been assisting the Federal Highway Administration (FHWA) to develop and provide technical support for large-scale simulation-based dynamic traffic assignment systems, for the past 10 years. He serves as an Associate Editor for Transportation Research Part C: Emerging Technologies. He has published more than 30 papers related to dynamic traffic assignment and rail operations research in Transportation Research Part B, Transportation Research Part C, EJOR and IEEE Transactions on ITS. His paper on single-track train timetabling is one of top 10 mostly cited papers in Transportation Research Part B during the period of 2007-2013. He is the principle developer of open-source package DTALite, light-weight open-source traffic assignment/simulation engine and NEXTA, a traffic data visualization platform, which have been used by a number of transportation planning agencies, with more than 3000 downloads from the Google Code website.  

Zhou is the co-chair of the IEEE ITS Society Technical Committee on Traffic and Travel Management, co-vice chair for Institute for Operations Research and the Management Sciences, Railway Applications Section (RAS). He also serves as the chair for the Network Equilibrium Modeling Subcommittee in TRB Committee on Transportation Network Modeling (ADB30). He is also the co-inventor of Key2SafeDriving technologies, which has been reported by more than 300 media outlets including New York Times, Wall Street Journal and National Public Radio.

Students advised by Zhou have won a number of awards: Jeffrey Taylor received the Council of University Transportation Centers Pikarsky Award-Science & Technology-MS, 2014, Tie Shi won the First Prize in Management Science in Railroad Applications Paper Contest, Institute for Operations Research and Management Science (INFORMS), 2014. Tao Xing, Kenneth Williams, Rohan Madtha, Daniel Van Tassell won Windows Mobile Award, Microsoft's Imagine Cup Student Technology Competition, 2009, out of 125 participating student teams in the U.S.

Research Interests
======
**Transportation planning**: Dynamic traffic assignment, traffic demand analysis

**Transportation system operations and control**: Traffic flow estimation and prediction, traffic flow theory, real-time traveler information system

**Logistics and intermodal transportation systems**: Train timetabling and real-time dispatching, scheduling for transit, rail and seaport systems

**Computer applications for Intelligent Transportation Systems**: Visualization analytics, distributed computing and communications

**Operations research**: Nonlinear programming, integer programming, network optimization




Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
