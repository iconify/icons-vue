<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5tm4wb9m"/><path class="hjq5dwm9u"/><path class="e5zikyigd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-return" /></template>
<style>
.e5zikyigd {
  d: path("M8.25 15.75L5.5 18.5l2.75 2.75m-5.5-6v6.5");
}

.g5tm4wb9m {
  d: path("M3.5 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m10 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hjq5dwm9u {
  d: path("M7 8.5h4l3.5-5l2.5 5m3.5 6.5v1a2.5 2.5 0 0 1-2.5 2.5H5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
