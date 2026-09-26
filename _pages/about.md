---
layout: about
title: about
permalink: /
subtitle: Associate Professor, <a href='https://www.swufe.edu.cn/'>Southwestern University of Finance and Economics</a>

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>School of Computing and Artificial Intelligence</p>
    <p>Southwestern University of Finance and Economics</p>
    <p>Chengdu, China</p>
    <p>wenlj@swufe.edu.cn</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 8 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am an **Associate Professor** and Master's supervisor at the School of Computing and Artificial Intelligence, [Southwestern University of Finance and Economics (SWUFE)](https://www.swufe.edu.cn/). I received my Ph.D. in Engineering from the [University of Electronic Science and Technology of China (UESTC)](https://www.uestc.edu.cn/) in 2021. Before joining SWUFE, I was a researcher at **Huawei Noah's Ark Lab** (2021–2023), where I gained extensive experience in engineering and research management, and I continue to maintain close ties with industry.

My research interests include:

- **Large Language Models**
- **AI Agents**
- **Multimodal Learning**
- **Representation Learning & Self-Supervised Learning**
- **AI for Quantitative Finance**

I have published over 30 papers in top-tier journals and conferences, including TPAMI, NeurIPS, ICLR, ACL, CVPR, ECCV, and ICCAD.

<div class="alert alert-info" role="alert" markdown="1">
**Join us.** I am committed to teaching and mentoring every student. Students interested in multimodal learning, large language models, AI agents, or self-supervised learning are welcome to apply for graduate study, and outstanding undergraduates are welcome to join the group. We value passion for research, self-motivation, a long-term commitment to steady effort, and a collaborative spirit. Please [email me](mailto:wenlj@swufe.edu.cn) — I will reply and arrange a conversation as soon as possible.
</div>

<style>
  /* Home page: pin the photo + contact info in a left sidebar column on wide screens */
  @media (min-width: 992px) {
    .container[role="main"] {
      max-width: 1200px;
    }
    .post {
      display: grid;
      grid-template-columns: 250px minmax(0, 1fr);
      column-gap: 48px;
      align-items: start;
    }
    .post > article {
      display: contents;
    }
    .post > header,
    .post > article > * {
      grid-column: 2;
    }
    .post > article > .profile {
      grid-column: 1;
      grid-row: 1 / span 50;
      position: sticky;
      top: 90px;
      float: none;
      width: auto;
      margin: 0;
    }
    .post > article > .profile .more-info {
      text-align: left;
    }
  }
</style>
