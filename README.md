Acme-Schlong
============

Fun with Acme::Schlong!

WARNING
=======

This is a pure alpha release -- if you like to contribute, hack away!

SYNOPSIS
--------

_This is a raw import from an old stage_

I remember, years ago, to have found one arcane incantation on the shell to calcuate your schlong size on your Linux box.

I was both amazed and curious and immediately tried it on my system (which happened to be OSX and it didn't work...).

Next, I tried it on the university's computers. It was way too cool.

Then, years later, I have found Perl::Achievements. It's a fun module.

It's a nice go-ahead-and-contribute-module. I wrote Perl::Achievements::Achievement::SchwartzianTransform for the fun of it.

So here is Acme::Schlong. Go ahead, contribute!

BTW: The arcane incantation was:

     echo `uptime|grep days|sed 's/.*up \([0-9]*\) day.*/\1\/10+/'; cat /proc/cpuinfo|grep MHz|awk '{print $4"/30 +";}'; free|grep '^Mem' | awk '{print $3"/1024/3+"}'; df -P -k -x nfs | grep -v 1k | awk '{if ($1 ~ "/dev/(scsi|sd)"){ s+= $2} s+= $2;} END {print s/1024/50"/15+70";}'`|bc|sed 's/\(.$\)/.\1cm/'

TODO
----

* Find good ways to calculate the following:
    * number of users logged in on the system (one user with 9 shells is 1 user.)
    * harddisk size
    * memory used
    * swap used
    * harddisk free space
    * uptime in minutes
    * running time in minutes
    * average load
* Find good infrastructure so that contributors can:
    * easily extend to new metrics
    * calculate the new schlong size
    * all roles/subclasses are used
* Build Task:: Distribution so that everybody can keep his own stuff?
* Versioning so that you can say "By metric XYZ your schlong size is XYZ" ?
* More robust OS-specific stuff.
* Send reports to some website