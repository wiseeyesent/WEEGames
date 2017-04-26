.. title: WEEChing
.. slug: weeching
.. date: 2017-04-25 17:32:49 UTC-05:00
.. tags: Projects,Games 
.. category: games
.. link: 
.. description: I Ching generator reading from deoxy.org
.. type: text

Download:
*********
`Source </files/weeching>`_

Info:
*****
A perl/curl based I Ching generator that retrieves & parses readings from `<http://deoxy.org/iching/>`_

This project was developed quite some time ago. I have no idea when I first wrote this version, but my `first mention <http://news.wiseeyesent.com/posts/2014/10/weeching-down.html>`_ of it was from 2014-10, when I noticed that `deoxy.org <http://deoxy.org>`_ was down (as it is wont to do) causing the disruption of my application.

Previous versions were originally written in Java and Objective-C using an internal reading database, making them non-reliant upon external systems. I have no idea if I still have that code somewhere, but may look for it in the future. 

I'm currently working on developing an API using the `Django REST Framework. <http://www.django-rest-framework.org/>`_ The intention being to create an I Ching API, since there are so many sites out there, but none of which I've found to be text browser friendly.

Once the API is up and running, then I plan on making a website front end for it using PHP that should be text browser friendly.

Specifications:
***************
- perl
- curl/libcurl
