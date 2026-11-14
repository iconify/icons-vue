<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="awzy1dxlv"/><path class="fvfsnmbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liquify" /></template>
<style>
.awzy1dxlv {
  d: path("M9 3c0 4.5-2.5 5.5-2.5 9S9 16.5 9 21m6-18c0 4.5 2.5 5.5 2.5 9S15 16.5 15 21");
}

.fvfsnmbzl {
  d: path("M3 9c4.5 0 5.5-2.5 9-2.5S16.5 9 21 9M3 15c4.5 0 5.5 2.5 9 2.5s4.5-2.5 9-2.5m-11-3a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
