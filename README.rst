Prototype Power
===============

A module in the Eurorack format that provides power pins and basic signals for prototyping.

Features
--------

Power Headers
^^^^^^^^^^^^^

Power headers are broken out at the front panel

* 16P IDC connector with Eurorack-standard pinout for power distribution
* 1x3 headers for +12V, +5V, ground, and -12V

Buffers/DC Outputs
^^^^^^^^^^^^^^^^^^

Two buffers are provided. The input of the second is normaled to the input of the first, enabling signal duplication.

* The first buffer is connected internally to a DC input with an adjustable :math:`\pm 10V` range. That connection is broken when the external input for buffer 1 is used.
* The input for the second buffer is connected internally (normaled) to the input for the first. That connection is broken when the external input for buffer 2 is used.

Gate and Envelope Generator
^^^^^^^^^^^^^^^^^^^^^^^^^^^

A 5V gate signal can be generated in one-shot (push button) or oscillator mode. Both the pulse length and frequency can be adjusted. The gate signal is also fed into a simple AR envelope with controls for attack and release, and the envelope is output.
