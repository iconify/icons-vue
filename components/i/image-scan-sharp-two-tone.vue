<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dahhbepwr"/><path class="mainm2bib"/><path class="isy2lrdil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-scan-sharp-two-tone" /></template>
<style>
.dahhbepwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12L14 21C14 21.5523 13.5523 22 13 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2L13 2C13.5523 2 14 2.4477 14 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.isy2lrdil {
  fill: currentColor;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

.mainm2bib {
  d: path("M3 18L9 12L12.0801 15.0801C12.3353 15.3353 12.6626 15.481 13 15.5128M17 2L17 3L17 10L17 11M17 22L17 21L17 14L17 13M21 21L21 20L21 18L21 17M21 15L21 14L21 10L21 9M21 7L21 6L21 4L21 3M13 21L3 21L3 3L13 3M13 23L13 22L13 21L13 15.5128L13 3L13 2L13 1");
}

</style>
