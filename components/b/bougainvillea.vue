<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-o90795g"/><path class="hb1-501bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bougainvillea" /></template>
<style>
.hb1-501bp {
  d: path("M18 4a2 2 0 0 1 0 4a2 2 0 0 1-4 0a2 2 0 0 1 0-4a2 2 0 0 1 4 0M9 9a2 2 0 0 1 0 4a2 2 0 0 1-4 0a2 2 0 0 1 0-4a2 2 0 0 1 4 0m3.5 7c3-1 6 .5 7 3c-3 .5-6-.5-7-3M16 6h.01M7 11h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-o90795g {
  d: path("M9 21.5c0-5 7-6 7-11.5m-6 8.5L7 15");
}

</style>
