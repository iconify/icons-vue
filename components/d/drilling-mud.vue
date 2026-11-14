<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u51upubhw"/><path class="lhow-7p1s"/><path class="hojf93wic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drilling-mud" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hojf93wic {
  d: path("M2 3.5h8q2 0 2 2v2m0 2.75V15");
}

.lhow-7p1s {
  fill: currentColor;
  d: path("M3 14q3-2 6 0t6 0t6 0v7H3Z");
}

.u51upubhw {
  d: path("M3 10v11h18V10");
}

</style>
