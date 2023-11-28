---
title: About
layout: default
permalink: /about/
---

<ul>
    {% for member in site.data.members %}
        <li>
            {{ member.pic }}<br />
            {{ member.name }}<br />
            {{ member.position }}<br />
            {{ member.expertise }}<p></p>
        </li>
    {% endfor %}
</ul>
