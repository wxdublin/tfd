TFD is a plugin for the [DECAF](http://code.google.com/p/decaf-platform/) dynamic binary analysis framework.
It enables to trace a selected x86 process on the guest OS. It can produce a instruction-level trace of the execution, a log of the heap allocations by the process, and memory snapshots at a point in the execution (e.g., at trace start or end).

TFD is an evolution of the Tracecap plugin that run on top of [TEMU](http://bitblaze.cs.berkeley.edu/temu.html) and is part of the [Bitblaze](http://bitblaze.cs.berkeley.edu/) binary analysis platform.

[Download TFD 1.0](http://software.imdea.org/~juanca/downloads/tfd_1.0.tar.gz)

Note that currently only DECAF 1.2 and DECAF 1.3 are supported

In addition to the TFD plugin, there is also libtracereader, a C parser for the execution traces produced by TFD and Tracecap, and trace\_creader a small utility that uses libtracereader to parse and dump the trace contents in a "human-understandable" format.

[Download trace\_creader 1.0](http://software.imdea.org/~juanca/downloads/trace_creader_1.0.tar.gz)

Send your questions to tfd-discuss@googlegroups.com