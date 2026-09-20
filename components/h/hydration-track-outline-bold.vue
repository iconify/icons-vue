<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lt_3_vk1y"/><path class="c6uw-ccfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hydration-track-outline-bold" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.lt_3_vk1y {
  d: path("M7 21V8l2.5 -2.5V3h5v2.5L17 8v13Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
