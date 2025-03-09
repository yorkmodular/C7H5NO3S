# C7H5NO3S - harmonic 'enhancer'

This module is based on a schematic called a 'harmonic sweetener', a schematic for which I found in a 1970s electronics magazine. The input signal is paralleled with a pair of cascaded Sallen-Key high-pass filters (fixed frequency in the original schematic, tunable in this one). The filtered signal, with the lower frequency harmonics attenuated, is then remixed with the input. To add a bit of interest, the filtered signal also has a clipping section (provided courtesy of two LEDs) with adjustable gain in order to give the filtered signal a bit more presence.

Obviously it works best with harmonic-rich signals (eg. sawtooth and square waveforms) but you can get interesting results from triangle-based waveforms.

What's in a name?

C<sub>7</sub>H<sub>5</sub>NO<sub>3</sub>S is the chemical formula for saccharine, which Wikipedia describes thus:

<i>"[it] is about 500 times sweeter than sucrose, but has a bitter or metallic aftertaste&nbsp;especially at high concentrations"</i>

which is actually a pretty apt description of what the module does (and that's the pearl of wisdom on the rear side of the faceplate) - it can add a bit of sweetness to a sound in small doses, but rapidly becomes rather overpowering once you start to crank it up.

The graphic on a faceplate? That's a saccharine molecule, because why the hell not.

This is a 100% through-hole build and there are no wilfully weird components - potentiometer and capacitor values for the two high-pass filters are those that I use in pre-assembled modules but feel free to experiment. There's probably more mileage in fiddling with the capacitor values than with the range of the pot. Unless stated otherwise, all pots are linear taper.

Red LEDs are recommended for the clipping diodes - the lower the forward voltage the better; I use LEDs with a 1.7V voltage drop

Jumpers J1-J4 should have bridges attached across two of the pins - these will determine how the filter pots behave.
