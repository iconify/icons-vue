<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGFIT4fcbw" x1="-232.591" x2="-232.527" y1="266.35" y2="266.35" gradientTransform="rotate(105.39 -52937.69 -10818.9)scale(243.14 -243.14)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient><linearGradient id="SVGkfnpSbpj" x1="-232.579" x2="-232.515" y1="267.655" y2="267.655" gradientTransform="matrix(190.987 150.5 150.5 -190.987 4142.028 86141.279)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="ysv71mbwx"/><path class="w9if9bp5z"/><path class="bbh-3dqzg"/><path fill="url(#SVGFIT4fcbw)" class="wk2q7acqr"/><path class="y1_s1iiis"/><path class="wr4mhxxpp"/><path fill="url(#SVGkfnpSbpj)" class="u2a2v4b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cypress" /></template>
<style>
.bbh-3dqzg {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M11.924 13.233a2.61 2.61 0 0 1 2.458 1.6l.036.079l1.849-.623l-.04-.094a4.55 4.55 0 0 0-4.3-2.8a4.62 4.62 0 0 0-3.387 1.323a4.44 4.44 0 0 0-1.374 3.302a4.42 4.42 0 0 0 1.371 3.289a4.62 4.62 0 0 0 3.387 1.324a4.55 4.55 0 0 0 4.3-2.8l.04-.094l-1.852-.624l-.035.083a2.56 2.56 0 0 1-2.456 1.595A2.6 2.6 0 0 1 10 18a2.73 2.73 0 0 1-.781-1.978a2.77 2.77 0 0 1 .781-2a2.6 2.6 0 0 1 1.928-.792Z");
}

.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.u2a2v4b_a {
  d: path("m17.488 26.06l-.462 1.11a.61.61 0 0 1-.538.378q-.234.01-.473.011A11.786 11.786 0 0 1 4.571 18.51l-1.852.415a13.52 13.52 0 0 0 4.73 7.514a13.75 13.75 0 0 0 8.546 3h.028c.182 0 .364 0 .544-.011a2.52 2.52 0 0 0 2.217-1.543l.6-1.45l-1.9-.375Z");
}

.w9if9bp5z {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m23.5 11.561l-2.635 6.612l-2.651-6.612h-2.17l3.719 9.025l-2.643 6.364l1.9.375l6.536-15.764z");
}

.wk2q7acqr {
  d: path("M22.251 25.8a11.617 11.617 0 0 0 4.106-15.214l1.682-.869a13.483 13.483 0 0 1-4.768 17.671z");
}

.wr4mhxxpp {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M11.049 3.444a13.67 13.67 0 0 1 17.065 6.433l-1.688.858A11.765 11.765 0 0 0 11.74 5.2l-.691-1.753Z");
}

.y1_s1iiis {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M2.905 19.562a13.4 13.4 0 0 1-.484-3.574A13.58 13.58 0 0 1 11.14 3.4l.684 1.755a11.69 11.69 0 0 0-7.5 10.832a11.5 11.5 0 0 0 .416 3.075Z");
}

.ysv71mbwx {
  d: path("M15.5 2.012A14 14 0 1 1 2.017 16.5A14.01 14.01 0 0 1 15.5 2.012");
}

</style>
