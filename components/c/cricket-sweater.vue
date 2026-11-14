<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s50ix5yvk"/><path class="h_vgq7qci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cricket-sweater" /></template>
<style>
.h_vgq7qci {
  d: path("M8.75 6.75L12 11.5l3.25-4.75M6.5 18h11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s50ix5yvk {
  d: path("M8.5 3L3 5.5l.5 6h3V21h11v-9.5h3l.5-6L15.5 3L12 8Z");
}

</style>
