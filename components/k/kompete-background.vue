<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGI9B9dc6c)" class="r4i437pya"/><path class="ckvp8zzox"/></g><defs><linearGradient id="SVGI9B9dc6c" x1="6.073" x2="18.036" y1="17.837" y2="8.373" gradientUnits="userSpaceOnUse"><stop class="unhl4jb9f"/><stop offset="1" class="l2kdgjbto"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kompete-background" /></template>
<style>
.ckvp8zzox {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.571 20V4H8v6.623L14.354 4h5.075l-6.84 6.943L19.429 20h-4.572l-4.766-6.52L8 15.6V20z");
}

.ft5dv1b6b {
  fill: none;
}

.l2kdgjbto {
  stop-color: var(--svg-color--6c0c0d, #6c0c0d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.unhl4jb9f {
  stop-color: var(--svg-color--090909, #090909);
}

</style>
