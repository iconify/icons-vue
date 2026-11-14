<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eaawogbch"/><path class="n-uxbyb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-pitch" /></template>
<style>
.eaawogbch {
  d: path("M8.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-uxbyb1s {
  d: path("M11.5 6.5q2.5 5.5 0 11m7-11q-2.5 5.5 0 11M3.5 8h3m-4 4h3m-2 4h3");
}

</style>
