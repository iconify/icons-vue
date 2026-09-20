<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bo51iypxr"/><path class="e771rwjjh"/><path class="xysie__pz"/><path class="se-pwqb_b"/><path class="km3h1bbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cyclone-outline-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.e771rwjjh {
  d: path("M9 17A5 5 0 0 1 9 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km3h1bbzc {
  d: path("M15 19h7");
}

.se-pwqb_b {
  d: path("M2 5h7");
}

.xysie__pz {
  d: path("M15 7a5 5 0 0 1 0 10");
}

</style>
