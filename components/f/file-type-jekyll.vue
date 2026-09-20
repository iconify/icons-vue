<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGQLuZYc1j" x1="-2.413" x2="-2.401" y1="32.987" y2="32.984" gradientTransform="matrix(561.015 0 0 -1011.593 1365.643 33384.042)" gradientUnits="userSpaceOnUse"><stop offset="0" class="oyem64b6r"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVG4sSZmeFG" x1="-4.202" x2="-4.191" y1="33.569" y2="33.566" gradientTransform="matrix(373.691 0 0 -614.108 1582.079 20634.253)" gradientUnits="userSpaceOnUse"><stop offset="0" class="anp5c3pdg"/><stop offset="1" class="j6621q89w"/></linearGradient></defs><path class="ieve63bdf"/><path fill="url(#SVGQLuZYc1j)" class="ebswlac8e"/><path fill="url(#SVG4sSZmeFG)" class="mf3ccmbqz"/><path class="o1kq_djim"/><path class="imejxtbud"/><g class="v27f9cbzg"><circle class="g000-cc5z"/><circle class="q6ls7zb-o"/><circle class="gq43ppboe"/><circle class="ww1uxvm1x"/><circle class="jwf1sjizz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jekyll" /></template>
<style>
.anp5c3pdg {
  stop-color: var(--svg-color--900, #900);
}

.ebswlac8e {
  d: path("M16.643 2.383a.3.3 0 0 0 0 .161a4.5 4.5 0 0 1-.027 1.648L8.362 25.669a3.077 3.077 0 0 0 5.748 2.2l8.254-21.48a5.7 5.7 0 0 1 1.085-1.233a1 1 0 0 0 .107-.121v-.013c0-.013.013-.013.013-.027c.215-.549-1.169-1.595-3.069-2.331s-3.631-.884-3.845-.322a.05.05 0 0 1-.013.04Z");
}

.g000-cc5z {
  cx: 13.952px;
  cy: 16.357px;
  r: 0.24px;
}

.gq43ppboe {
  cx: 13.126px;
  cy: 20.138px;
  r: 0.679px;
}

.ieve63bdf {
  d: path("M16.884 2.57a.3.3 0 0 0 0 .161a4.5 4.5 0 0 1-.027 1.648L8.6 25.857a3.077 3.077 0 0 0 5.748 2.2l8.257-21.481a5.7 5.7 0 0 1 1.085-1.232a1 1 0 0 0 .107-.121V5.21c0-.013.013-.013.013-.027c.214-.549-1.166-1.594-3.068-2.331s-3.63-.885-3.842-.322a.06.06 0 0 0-.016.04");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.imejxtbud {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.587 2.542a4.5 4.5 0 0 1-.027 1.643L8.361 25.6a3.06 3.06 0 0 0 1.77 3.928a2.6 2.6 0 0 0 .825.187a3.09 3.09 0 0 1-1.024-3.525l8.04-20.99a5.14 5.14 0 0 1-1.384-2.659Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j6621q89w {
  stop-color: var(--svg-color--e80000, #e80000);
}

.jwf1sjizz {
  cx: 13.459px;
  cy: 24.066px;
  r: 0.24px;
}

.mf3ccmbqz {
  d: path("M19.242 12.1L13.28 27.585a2.217 2.217 0 0 1-2.854 1.246A2.27 2.27 0 0 1 9.1 25.977l3.805-9.9a4.36 4.36 0 0 1 1.407-1.313c.938-.549 1.7-.429 2.733-.884a8.1 8.1 0 0 0 2.2-1.782Z");
}

.o1kq_djim {
  fill: var(--svg-color--333, #333);
  d: path("M22.133 4.547c.119-.31-.736-.928-1.909-1.381S18 2.6 17.885 2.907s.736.928 1.909 1.381s2.221.569 2.339.259");
}

.oyem64b6r {
  stop-color: var(--svg-color--919191, #919191);
}

.q6ls7zb-o {
  cx: 15.509px;
  cy: 18.08px;
  r: 0.359px;
}

.v27f9cbzg {
  fill: var(--svg-color--fff, #fff);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ww1uxvm1x {
  cx: 12.035px;
  cy: 21.394px;
  r: 0.359px;
}

</style>
