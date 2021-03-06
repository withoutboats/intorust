---
layout: tutorial
title: Shared borrows
title_img: /assets/images/shared_borrows.png
slug: shared borrows
description: How to have multiple references to the same data without copying
img: /assets/images/and.png
youtube_id: 61bFe3jqi1E
date: 2016.09.25
author: Nicholas D. Matsakis
time: 25min
exercises:
  - name: Shared borrows
    rust: _rust/20_sharing.rs
predecessors:
  - name: Ownership
    link: /tutorial/ownership
successors:
  - name: Mutable Borrows
    link: /tutorial/mutable-borrows
---

Continue from where the [ownership tutorial] left off. Learn how to
give temporary access to data with the `&` operator and `&T` types.

[ownership tutorial]: {% link _tutorials/10_Ownership.markdown %}
