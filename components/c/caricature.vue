<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m9ielbcdf"/><path class="s1jdutb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:caricature" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9ielbcdf {
  d: path("M12 2.5c5.5 0 8.5 3.5 8.5 8c0 5.5-5 11-8.5 11s-8.5-5.5-8.5-11c0-4.5 3-8 8.5-8");
}

.s1jdutb-m {
  d: path("M6.5 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 13.5l-1.75 3h3");
}

</style>
