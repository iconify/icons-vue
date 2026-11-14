<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-747lbuo"/><path class="pfn2qob0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beanie-kids" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-747lbuo {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.pfn2qob0y {
  d: path("M5 14c0-4.75 3-7 7-7s7 2.25 7 7M6.125 14h11.75a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875v-1.25A2.625 2.625 0 0 1 6.125 14m1.625 0v6.5M12 14v6.5m4.25-6.5v6.5");
}

</style>
