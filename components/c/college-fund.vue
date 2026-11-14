<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9iczrbja"/><path class="ukw2kwunr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:college-fund" /></template>
<style>
.g9iczrbja {
  d: path("M4 13.5c0-3.5 3.5-6 8-6s8 2.5 8 6c0 2.25-1.25 4-3.5 5V21H14v-1.75c-.75.25-1.25.25-2 .25s-1.25 0-2-.25V21H7.5v-2.5c-2.25-1-3.5-2.75-3.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ukw2kwunr {
  d: path("M4.5 12h-2v3h2M9.208 4.392l2.224-.91a1.5 1.5 0 0 1 1.136 0l2.224.91A1.13 1.13 0 0 1 14.75 6.5l-2.237.814a1.5 1.5 0 0 1-1.026 0L9.25 6.5a1.13 1.13 0 0 1-.042-2.108M7.75 12.25h.01");
}

</style>
