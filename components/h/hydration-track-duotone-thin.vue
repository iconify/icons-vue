<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4_2_okqa"/><path class="lt_3_vk1y"/><path class="c6uw-ccfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hydration-track-duotone-thin" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lt_3_vk1y {
  d: path("M7 21V8l2.5 -2.5V3h5v2.5L17 8v13Z");
}

.q4_2_okqa {
  fill: currentColor;
  d: path("M7 21V8l2.5 -2.5V3h5v2.5L17 8v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
