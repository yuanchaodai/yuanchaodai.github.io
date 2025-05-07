---
layout: page
title: 🎉 News
permalink: /
---

欢迎来到我的学术主页！

这里展示我的研究成果、项目和个人信息。

{% if site.data.news.items %}
  <div>
  {% for message in site.data.news.items %}
    <p>
      [<span><font color="blue">{{message.date}}</font></span>] {{message.content}}
    </p>
  {% endfor %}
  </div>
{% endif %}

