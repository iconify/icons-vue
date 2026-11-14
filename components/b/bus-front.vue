<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4-zk8jiv"/><path class="vfo0uzk_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-front" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfo0uzk_z {
  d: path("M9.25 8.5h5.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 9.25 8.5M8 16h.01M16 16h.01M7.5 19v2.5m9-2.5v2.5");
}

.y4-zk8jiv {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v7.75A4.375 4.375 0 0 1 15.125 19h-6.25A4.375 4.375 0 0 1 4.5 14.625v-7.75A4.375 4.375 0 0 1 8.875 2.5M8 5.5h8");
}

</style>
