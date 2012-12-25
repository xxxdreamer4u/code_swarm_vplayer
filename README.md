Code swarm for VPlayer
======================

The [code swarm](https://github.com/yixia/code_swarm) configuration for our VPlayer codebase, including several git and hg repositories.


How to output video file
========================

In code swarm root directory, `ffmpeg -f image2 -r 24 -i ./frames/%05d.png -sameq ./swarm.mov -pass 2`
