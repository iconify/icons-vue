<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m1lvaubhl"/><path class="w9nhvkswb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journey-planner" /></template>
<style>
.m1lvaubhl {
  d: path("m2.5 5l6-1.5l7 1.5l6-1.5V19l-6 1.5l-7-1.5l-6 1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9nhvkswb {
  d: path("M15.5 15s-3-2.5-3-4.5a3 3 0 0 1 6 0c0 2-3 4.5-3 4.5Zm-9 1h.01m2.74 0l2.5-.5");
}

</style>
