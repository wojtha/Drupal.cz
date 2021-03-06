The Basics
==========
VotingAPI is a framework for content voting and rating systems in Drupal. It does not directly provide any voting 'features' to users -- instead, it offers a consistent API for other module developers to build their voting and rating systems on top of. If you're an end user who just wants to rate nodes, check out some of the modules that use VotingAPI's framework:

SimpleVote
MediumVote
UserReview
Vote-Up-Down
LatestGreatest
LoveHate
Node Moderation

... and more to come.

If you're a developer who wants to build a voting or rating related module, check out API.txt in the VotingAPI directory.

Installation
============
Installing VotingAPI is pretty straightforward. Just copy the VotingAPI directory into your web site's /modules directory. Then, activate the module by visiting http://www.example.com/admin/modules, where example.com is the URL of your web site.

Requirements
============
VotingAPI requires Drupal 4.7 or later.

If Views.module and Actions.module are installed, additional functionality is available (like the ability to kick off workflow actions based on the results of a collaborative vote). These modules are not required, but they are very cool.