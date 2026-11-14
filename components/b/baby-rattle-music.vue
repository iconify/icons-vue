<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhgxgacwu"/><path class="euw94_xpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-rattle-music" /></template>
<style>
.euw94_xpb {
  d: path("M8.5 13.5V16a2.75 2.75 0 0 1 0 5.5a2.75 2.75 0 0 1 0-5.5m5-.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0V4C19 5 21 5.5 21 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qhgxgacwu {
  d: path("M3 8a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 3 8");
}

</style>
