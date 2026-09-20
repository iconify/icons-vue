<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG8Rf5Lb0F)" class="r4i437pya"/><path class="je_kzvl4x"/><path class="whb8hkb1b"/></g><defs><linearGradient id="SVG8Rf5Lb0F" x1="4" x2="19.997" y1="9.714" y2="9.319" gradientUnits="userSpaceOnUse"><stop class="d8vrfk-cj"/><stop offset="1" class="dtmhzusit"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kwenta-background" /></template>
<style>
.d8vrfk-cj {
  stop-color: var(--svg-color--c39a6f, #c39a6f);
}

.dtmhzusit {
  stop-color: var(--svg-color--9a6a3a, #9a6a3a);
}

.ft5dv1b6b {
  fill: none;
}

.je_kzvl4x {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 13.882l8-5.007V4L4 9.007zm16 0l-8-5.007V4l8 5.007z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.whb8hkb1b {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 10.118l8 5.007V20l-8-5.007zm16 0l-8 5.007V20l8-5.007z");
}

</style>
