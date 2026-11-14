<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brtkinouz"/><path class="enzz1bc_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chalk-line" /></template>
<style>
.brtkinouz {
  d: path("M3 14.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m1.5 4l-2 2M8.5 9l13-4m0-2.5V10");
}

.enzz1bc_j {
  d: path("M7 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
