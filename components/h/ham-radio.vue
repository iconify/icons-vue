<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ieu8e-a6d"/><path class="tl362pbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ham-radio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ieu8e-a6d {
  d: path("M6.5 10.5h11A3.5 3.5 0 0 1 21 14v3a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-3a3.5 3.5 0 0 1 3.5-3.5m9.5 0v-5");
}

.tl362pbwb {
  d: path("M6 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M19.031 3.75a3.5 3.5 0 0 1 0 3.5m-6.062 0a3.5 3.5 0 0 1 0-3.5");
}

</style>
