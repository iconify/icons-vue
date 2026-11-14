<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skdi0tb7c"/><path class="fwhsai78g"/><path class="qawz0cb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-usage-high" /></template>
<style>
.fwhsai78g {
  fill: currentColor;
  d: path("M8.5 6za1.25 1.25 0 0 1 1.25 1.25V17.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25V7.25A1.25 1.25 0 0 1 8.5 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qawz0cb-i {
  d: path("M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.skdi0tb7c {
  d: path("M8.5 2.5za4 4 0 0 1 4 4v11a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-11a4 4 0 0 1 4-4");
}

</style>
