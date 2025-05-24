# Pint
Simple init system made for Priism. Can probably be used to boot other distros.

## How to use
Services are executables (typically shell scripts) that go in `/usr/share/pint/pint.d`.

Specify init system to boot in `/usr/share/pint/handoff.conf`.

`init` itself goes in `/sbin/`.

Depending on the location of some binaries (we don't have PATH in runlevel 1), you may need to make slight modifications to `/sbin/init`.

