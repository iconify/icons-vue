<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r06x6ebtw"/><path class="d6j4ff3zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diaphragm" /></template>
<style>
.d6j4ff3zr {
  fill: currentColor;
  d: path("M2.5 20.5c4.5-4.75 14.5-4.75 19 0C17 18 7 18 2.5 20.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r06x6ebtw {
  d: path("M10.5 6c-3-.5-7 2.5-7 7c0 2 1.25 2.75 3 2.25c2-.5 4-1.25 4-2.75Zm3 0c3-.5 7 2.5 7 7c0 2-1.25 2.75-3 2.25c-2-.5-4-1.25-4-2.75ZM12 2.5v4M10.5 8L12 6.5L13.5 8");
}

</style>
