<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzci78fjf"/><path clip-rule="evenodd" class="h_07bdcra"/><path class="wwilclk2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gun-duotone" /></template>
<style>
.h_07bdcra {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 4L3 4C2.5411 4 2.1411 4.3123 2.0299 4.7575L1.0299 8.7575C1.01 8.8368 1 8.9182 1 9C1 10.1046 1.8954 11 3 11L3.656 11L11.244 11L16 11L18.5 11C18.7652 11 19.0196 10.8946 19.2071 10.7071L19.9142 10L20.5 10C21.8807 10 23 8.8807 23 7.5L23 6C23 4.8954 22.1046 4 21 4L19 4Z");
  stroke: none;
}

.mzci78fjf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.244 11C11.2421 11.0066 11.24 11.0132 11.2379 11.0197L10.2034 14.2269L8.3794 19.8817C7.9926 21.14 6.8299 22 5.5119 22L4.1881 22C2.1785 22 0.7371 20.0628 1.3146 18.1379C1.3181 18.1262 1.3218 18.1145 1.3258 18.1029L3.0034 13.1776C3.1181 12.8449 3.2304 12.3327 3.2273 11.8186C3.2253 11.4966 3.1791 11.222 3.0946 11L3.656 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wwilclk2j {
  d: path("M19 5V3M16 10L14.8292 12.3416C14.321 13.358 13.2822 14 12.1459 14H9.5");
}

</style>
