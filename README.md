hr in Perl
-----------

See [hr](https://github.com/LuRsT/hr).

FAQ
---

Q: If you encountered the following error:

    Can't locate sys/ioctl.ph in @INC (did you run h2ph?)

A: Please try running this command:

    cd /usr/include && h2ph *.h sys/*.h
