---
layout: page
mathjax: true
permalink: /project/
title: Course project
---

### Overview

The Course Project is an opportunity for you to apply what you have learned in class to a
problem of your interest. Potential projects usually fall into these two tracks:

* **Applications:** If you're coming to the class with a specific background and interests (e.g. biology,
      engineering, physics), we'd love to see you apply ConvNets to problems related to your
      particular domain of interest. Pick a real-world problem and apply ConvNets to solve it.
* **Models:** You can build a new model (algorithm) with ConvNets, or a new variant of existing models,
      and apply it to tackle vision tasks. This track might be more challenging, and sometimes
      leads to a piece of publishable work.

To get a better feeling for what we expect from your projects, we encourage you to take a
look at the project reports from previous years of Stanford/CS231n and Berkeley/CS294-129:
- [CS231n/Spring 2017](http://cs231n.stanford.edu/2017/reports.html)
- [CS231n/Winter 2016](http://cs231n.stanford.edu/2016/reports.html)
- [CS231n/Winter 2015](http://cs231n.stanford.edu/2015/reports.html)
- [CS294-129/Fall 2016](https://bcourses.berkeley.edu/courses/1453965/pages/projects)

To inspire ideas, you might also look at recent deep learning publications from top-tier
conferences, as well as other resources below.
- [CVPR](http://openaccess.thecvf.com/CVPR2017.py): IEEE Conference on Computer Vision and Pattern Recognition
- [ICCV](http://openaccess.thecvf.com/ICCV2017.py): International Conference on Computer Vision
- [ECCV](http://www.eccv2016.org/main-conference/): European Conference on Computer Vision
- [NIPS](https://papers.nips.cc/): Neural Information Processing Systems
- [ICLR](https://openreview.net/group?id=ICLR.cc/2018/Conference): International Conference on Learning Representations
- [ICML](https://icml.cc/Conferences/2017/Schedule?type=Poster): International Conference on Machine Learning
- [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
- [Kaggle challenges](http://www.kaggle.com/): An online machine learning competition website. For example, a [Yelp classification challenge](https://www.kaggle.com/c/yelp-restaurant-photo-classification).

For applications, this type of projects would involve careful data preparation, an appropriate
loss function, details of training and cross-validation and good test set evaluations and model
comparisons. Don't be afraid to think outside of the box. Some successful examples can be found
below:
- [Teaching Deep Convolutional Neural Networks to Play Go](http://arxiv.org/abs/1412.3409)
- [Playing Atari with Deep Reinforcement Learning](http://arxiv.org/abs/1312.5602)
- [Winning the Galaxy Challenge with convnets](http://blog.kaggle.com/2014/04/18/winning-the-galaxy-challenge-with-convnets/)
- [Recommending music on Spotify with deep learning](http://benanne.github.io/2014/08/05/spotify-cnns.html)

ConvNets also run in real time on mobile phones and Raspberry Pi's - building an interesting
mobile application could be a good project. If you want to go this route you might want to
check out <a href="https://www.tensorflow.org/mobile/">TensorFlow Mobile / Lite</a> or
<a href="https://caffe2.ai/docs/mobile-integration.html">Caffe2 iOS/Android integration</a>.

For models, ConvNets have been successfully used in a variety of computer vision tasks. This
type of projects would involve understanding the state-of-the-art vision models, and building
new models or improving existing models for a vision task. The list below presents some papers
on recent advances of ConvNets in the computer vision community.

#### Image Classification
- <a href="http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf">[Krizhevsky et al.]</a>,
- <a href="http://arxiv.org/abs/1409.0575">[Russakovsky et al.]</a>,
- <a href="http://arxiv.org/abs/1409.4842">[Szegedy et al.]</a>,
- <a href="http://arxiv.org/abs/1409.1556">[Simonyan et al.]</a>,
- <a href="http://arxiv.org/abs/1406.4729">[He et al.]</a>,
- <a href="https://arxiv.org/abs/1608.06993">[Huang et al.]</a>,
- <a href="https://arxiv.org/abs/1709.01507">[Hu et al.]</a>
- <a href="https://arxiv.org/abs/1707.07012">[Zoph et al.]</a>

#### Object detection
- <a href="http://arxiv.org/abs/1311.2524">[Girshick et al.]</a>,
- <a href="https://arxiv.org/abs/1506.01497">[Ren et al.]</a>,
- <a href="https://arxiv.org/abs/1703.06870">[He et al.]</a>

#### Image segmentation 
- <a href="http://arxiv.org/abs/1411.4038">[Long et al.]</a>
- <a href="https://arxiv.org/abs/1505.04366">[Noh et al.]</a>
- <a href="http://ieeexplore.ieee.org/abstract/document/7913730/">[Chen et al.]</a>

#### Video classification
- <a href="http://cs.stanford.edu/people/karpathy/deepvideo/">[Karpathy et al.]</a>,
- <a href="http://arxiv.org/abs/1406.2199">[Simonyan and Zisserman]</a>
- <a href="https://arxiv.org/abs/1412.0767">[Tran et al.]</a>
- <a href="https://arxiv.org/abs/1705.07750">[Carreira et al.]</a>
- <a href="https://arxiv.org/abs/1711.07971">[Wang et al.]</a>

#### Scene classification
- <a href="http://places.csail.mit.edu/">[Zhou et al.]</a>

#### Face recognition
- <a href="http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Taigman_DeepFace_Closing_the_2014_CVPR_paper.pdf">[Taigman et al.]</a>
- <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Schroff_FaceNet_A_Unified_2015_CVPR_paper.pdf">[Schroff et al.]</a>
- <a href="http://cis.csuohio.edu/~sschung/CIS660/DeepFaceRecognition_parkhi15.pdf">[Parkhi et al.]</a>

#### Depth estimation
- <a href="http://www.cs.nyu.edu/~deigen/depth/">[Eigen et al.]</a>

#### Image-to-sentence generation
- <a href="http://cs.stanford.edu/people/karpathy/deepimagesent/">[Karpathy and Fei-Fei]</a>,
- <a href="http://arxiv.org/abs/1411.4389">[Donahue et al.]</a>,
- <a href="http://arxiv.org/abs/1411.4555">[Vinyals et al.]</a>
- <a href="https://arxiv.org/pdf/1502.03044.pdf">[Xu et al.]</a>
- <a href="https://arxiv.org/abs/1511.07571">[Johnson et al.]</a>

#### Visualization and optimization
- <a href="http://arxiv.org/pdf/1312.6199v4.pdf">[Szegedy et al.]</a>,
- <a href="http://arxiv.org/abs/1412.1897">[Nguyen et al.]</a>,
- <a href="http://arxiv.org/abs/1311.2901">[Zeiler and Fergus]</a>,
- <a href="http://arxiv.org/abs/1412.6572">[Goodfellow et al.]</a>,
- <a href="http://arxiv.org/abs/1312.6055">[Schaul et al.]</a>

You might also gain inspiration by taking a look at some popular computer vision datasets:

- <a href="http://www.cvpapers.com/datasets.html">Meta Pointer: A large collection organized by CV Datasets.</a>
- <a href="http://riemenschneider.hayko.at/vision/dataset/">Yet another Meta pointer</a>
- <a href="http://http://image-net.org/">ImageNet</a>: a large-scale image dataset for visual recognition organized by <a href="http://wordnet.princeton.edu/">WordNet</a> hierarchy
- <a href="http://groups.csail.mit.edu/vision/SUN/">SUN Database</a>: a benchmark for scene recognition and object detection with annotated scene categories and segmented objects
- <a href="http://places.csail.mit.edu/">Places Database</a>: a scene-centric database with 205 scene categories and 2.5 millions of labelled images
- <a href="http://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html">NYU Depth Dataset v2</a>: a RGB-D dataset of segmented indoor scenes
- <a href="http://mscoco.org/">Microsoft COCO</a>: a new benchmark for image recognition, segmentation and captioning
- <a href="http://yahoolabs.tumblr.com/post/89783581601/one-hundred-million-creative-commons-flickr-images">Flickr100M</a>: 100 million creative commons Flickr images
- <a href="http://vis-www.cs.umass.edu/lfw/">Labeled Faces in the Wild</a>: a dataset of 13,000 labeled face photographs
- <a href="http://human-pose.mpi-inf.mpg.de/">Human Pose Dataset</a>: a benchmark for articulated human pose estimation
- <a href="http://www.cs.tau.ac.il/~wolf/ytfaces/">YouTube Faces DB</a>: a face video dataset for unconstrained face recognition in videos
- <a href="http://crcv.ucf.edu/data/UCF101.php">UCF101</a>: an action recognition data set of realistic action videos with 101 action categories
- <a href="http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/">HMDB-51</a>: a large human motion dataset of 51 action classes
- <a href="http://activity-net.org/">ActivityNet</a>: A large-scale video dataset for human activity understanding
- <a href="http://moments.csail.mit.edu/">Moments in Time</a>: A dataset of one million 3-second videos

### Collaboration Policy

You can work in teams of up to <strong>2~3</strong> people. We do expect that projects done with
3 people have more impressive writeup and results than projects done with 2 people. To get a
sense for the scope and expectations for 2-people projects have a look at project reports from
previous years of Stanford/CS231n and Berkeley/CS294-129 (see above).

<!--
  <h2>Honor Code</h2>
  <p>
    You may consult any papers, books, online references, or publicly available implementations for
    ideas and code that you may want to incorporate into your strategy or algorithm, so long as you
    clearly cite your sources in your code and your writeup. However, under no circumstances may you
    look at another group’s code or incorporate their code into your project.
  </p>
  <p>
    If you are combining your course project with the project from another class, you must receive
    permission from the instructors, and clearly explain in the Proposal, Milestone, and Final Report
    the exact portion of the project that is being counted for CS 231n. In this case you must prepare
    separate reports for each course, and submit your final report for the other course as well.
  </p>
-->

### Important Dates
  <ul>
    <li>Project proposal: due Monday, April 22.</li>
    <li>Project milestone: due Monday, May 27.</li>
    <li>Final report: due Wednesday, July 3. <b>No late days.</b></li>
  </ul>

### Project Proposal
he project proposal should be one paragraph (200-400 words). Your project proposal should
describe:

<ul>
    <li>What is the problem that you will be investigating? Why is it interesting?</li>
    <li>What reading will you examine to provide context and background?</li>
    <li>What data will you use? If you are collecting new data, how will you do it?</li>
    <li>
      What method or algorithm are you proposing? If there are existing implementations, will you
      use them and how? How do you plan to improve or modify such implementations? You don't have
      to have an exact answer at this point, but you should have a general sense of how you will
      approach the problem you are working on.
    </li>
    <li>
      How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g.
      plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or
      compare your results (e.g. what performance metrics or statistical tests)?
    </li>
  </ul>
  
**Submission:** 
Please submit your proposal as a PDF file.

### Project Milestone
Your project milestone report should be between 2 - 3 pages using the  <a href="http://cvpr2017.thecvf.com/files/cvpr2017AuthorKit.zip">provided template</a>.
The following is a suggested structure for your report:

<ul>
      <li>Title, Author(s)</li>
      <li>Introduction: this section introduces your problem, and the overall plan for approaching your problem</li>
      <li>Problem statement: Describe your problem precisely specifying the dataset to be used, expected results and evaluation</li>
      <li>Technical Approach: Describe the methods you intend to apply to solve the given problem</li>
      <li>
      Intermediate/Preliminary Results: State and evaluate your results upto the milestone
      </li>
</ul>

**Submission:** 
Please submit your milestone report as a PDF file.

### Final Report

Your final write-up is required to be between <b>6 - 8</b> pages using the
<a href="http://www.pamitc.org/cvpr15/files/cvpr2015AuthorKit.zip">provided template</a>,
structured like a paper from a computer vision conference (CVPR, ECCV, ICCV, etc.).
Please use this template so we can fairly judge all student projects without worrying about
altered font sizes, margins, etc. After the class, we will post all the final reports online
so that you can read about each others' work. If you do not want your writeup to be posted
online, then please let us know at least a week in advance of the final writeup submission
deadline.

The following is a suggested structure for your report, as well as the rubric that we will
follow when evaluating reports. You don't necessarily have to organize your report using
these sections in this order, but that would likely be a good starting point for most projects.

<ul>
    <li><b>Title, Author(s)</b></li>
    <li>
      <b>Abstract</b>: Briefly describe your problem, approach, and key results. Should be no more
      than 300 words.
    </li>
    <li>
      <b>Introduction (10%)</b>:
      Describe the problem you are working on, why it's important, and an overview of your results
    </li>
    <li>
      <b>Related Work (10%)</b>:
      Discuss published work that relates to your project. How is your approach similar or different
      from others?
    </li>
    <li>
      <b>Data (10%)</b>:
      Describe the data you are working with for your project. What type of data is it? Where did it
      come from? How much data are you working with? Did you have to do any preprocessing, filtering,
      or other special treatment to use this data in your project?
    </li>
    <li>
      <b>Methods (30%)</b>:
      Discuss your approach for solving the problems that you set up in the introduction. Why is
      your approach the right thing to do? Did you consider alternative approaches? You should
      demonstrate that you have applied ideas and skills built up during the quarter to tackling
      your problem of choice. It may be helpful to include figures, diagrams, or tables to
      describe your method or compare it with other methods.
    </li>
    <li>
      <b>Experiments (30%)</b>:
      Discuss the experiments that you performed to demonstrate that your approach solves the
      problem. The exact experiments will vary depending on the project, but you might compare
      with previously published methods, perform an ablation study to determine the impact of
      various components of your system, experiment with different hyperparameters or architectural
      choices, use visualization techniques to gain insight into how your model works, discuss
      common failure modes of your model, etc. You should include graphs, tables, or other figures
      to illustrate your experimental results.
    </li>
    <li>
      <b>Conclusion (5%)</b>
      Summarize your key results - what have you learned? Suggest ideas for future extensions
      or new applications of your ideas.
    </li>
    <li>
      <b>Writing / Formatting (5%)</b>
      Is your paper clearly written and nicely formatted?
    </li>
    <li>
      <b>Supplementary Material</b>, not counted toward your 6-8 page limit and submitted as
      a separate file. Your supplementary material might include:
      <ul>
        <li>
          Source code (if your project proposed an algorithm, or code that is relevant and important
          for your project.).
        </li>
        <li>Cool videos, interactive visualizations, demos, etc.</li>
      </ul>
      Examples of things to not put in your supplementary material: 
      <ul>
        <li>The entire PyTorch/TensorFlow Github source code.</li>
        <li>Any code that is larger than 10 MB.</li>
        <li>Model checkpoints.</li>
        <li>A computer virus.</li>
      </ul>
    </li>
  </ul>

**Submission**:
    You will submit your final report as a PDF and your supplementary material as a separate PDF
    or ZIP file.

**Additional Submission Requirements**:
    We will also ask you do do the following when you submit your project report:
  <ul>
    <li>
      <b>Your report PDF should list <i>all</i> authors who have contributed to your work; enough to
        warrant a co-authorship position.</b> This includes people not enrolled in i@DL such as
      faculty/advisors if they sponsored your work with funding or data, significant mentors (e.g.,
      PhD students or postdocs who coded with you, collected data with you, or helped draft your
      model on a whiteboard). All authors should be listed directly underneath the title on your PDF.
      Include a footnote on the first page indicating which authors are not enrolled in i2DL. All
      co-authors should have their institutional/organizational affiliation specified below the title.
    </li>
    <ul>
      If you have non-i2DL contributors, you will be asked to describe the following:
      <li>
        <b>Specify the involvement of non-I2DL contributors</b>
        (discussion, writing code, writing paper, etc). For an example, please see the author
        contributions for <a href="https://www.nature.com/nature/journal/v529/n7587/full/nature16961.html#author-information" target="_blank">AlphaGo (Nature, 2016)</a>.
        <li>
          <b>Specify whether the project has been submitted to a peer-reviewed conference or journal.</b>
          Include the full name and acronym of the conference (if applicable). For example: Neural
          Information Processing Systems (NIPS). This only applies if you have already
          <i>submitted</i> your paper/manuscript and it is under review as of the report deadline.
      </li>
    </ul>
    <li>
      <b>Any code that was used as a base for projects must be referenced and cited in the body of the paper.</b>
      This includes I2DL assignment code, finetuning example code, open-source, or Github
      implementations. You can use a footnote or full reference/bibliography entry.
    </li>
    <li>
      <b>If you are using this project for multiple classes, submit the other class PDF as well.</b>
      Remember, it is an honor code violation to use the same final report PDF for multiple classes.
    </li>
  </ul>

In summary, include all contributing authors in your PDF; include detailed co-author
information; tell us if you submitted to a conference, cite any code you used, and submit your
dual-project report (e.g., submitted for more than one course).

