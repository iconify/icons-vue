<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWFg5Cerq)" class="r4i437pya"/><path class="b23586b9a"/></g><defs><linearGradient id="SVGWFg5Cerq" x1="6.335" x2="18.27" y1="6.065" y2="15.74" gradientUnits="userSpaceOnUse"><stop class="ldk7oegqh"/><stop offset="1" class="sta_5o_je"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cnfi-background" /></template>
<style>
.b23586b9a {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 4c-3.95.5-7 3.89-7 8s3.05 7.5 7 8v-2.085a6 6 0 0 1 0-11.83zm2 16c3.95-.5 7-3.89 7-8s-3.05-7.5-7-8v2.085a6 6 0 0 1 4.02 2.63c.065.325.005.81-.4 1.085a1.1 1.1 0 0 1-1.27 0v.01a4 4 0 1 0-.09 4.51v.02a1.15 1.15 0 0 1 1.455-.205c.38.25.475.61.45.925A6 6 0 0 1 13 17.915zm4.5-8a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.ft5dv1b6b {
  fill: none;
}

.ldk7oegqh {
  stop-color: var(--svg-color--ff5300, #ff5300);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sta_5o_je {
  stop-color: var(--svg-color--fbb705, #fbb705);
}

</style>
