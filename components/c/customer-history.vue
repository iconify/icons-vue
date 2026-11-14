<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_8ldnsjb"/><path class="ly0allbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customer-history" /></template>
<style>
.c_8ldnsjb {
  d: path("M13.534 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.75 6.5-4.75c.597 0 1.175.055 1.724.159M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m9.5 9.5a3.25 3.25 0 1 1 1.5 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ly0allbrh {
  d: path("m13.25 16.5l1.5 1.5l1.5-1.5");
}

</style>
