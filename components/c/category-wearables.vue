<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uoq-qmz_d"/><path class="mwb6bzb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-wearables" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwb6bzb8j {
  d: path("M8.25 12H10l1.25-3.5l1.75 7l1.25-3.5h1.5");
}

.uoq-qmz_d {
  d: path("M10.75 4.5h2.5a5.25 5.25 0 0 1 5.25 5.25v4.5a5.25 5.25 0 0 1-5.25 5.25h-2.5a5.25 5.25 0 0 1-5.25-5.25v-4.5a5.25 5.25 0 0 1 5.25-5.25m-2.25 0v-2h7v2m-7 15v2h7v-2");
}

</style>
