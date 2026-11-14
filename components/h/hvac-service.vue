<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0cic1b0g"/><path class="e4lo419bt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hvac-service" /></template>
<style>
.d0cic1b0g {
  d: path("M10 10c-1.5 1-4.75.5-5.5-1.75C4 6.5 5.75 4.5 7.5 5.5C9 6.5 9.25 8 10 10m2 0c-.25-2 2-4.5 4.25-4c1.75.5 2.5 3 .75 4c-1.5.75-3 .25-5 0m-1 1.75c1.75.75 2.75 3.75 1.25 5.5C11 18.5 8.5 18 8.5 16c0-1.75 1.25-2.75 2.5-4.25");
}

.e4lo419bt {
  d: path("M9.5 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11.72 5.903a2 2 0 1 1-1.623-1.623M15 21l2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
