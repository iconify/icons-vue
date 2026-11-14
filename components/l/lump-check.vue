<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yg_fy8b4q"/><path class="wmzn5gm0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lump-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmzn5gm0b {
  d: path("M10.25 8.5c.5.75 2 .75 2.5 0M2.5 21h19");
}

.yg_fy8b4q {
  d: path("M2.5 17.5h5c.5-3.25 7.5-3.25 8 0h6M14 2.5v7c0 1.4-1.1 2.5-2.5 2.5S9 10.9 9 9.5v-7");
}

</style>
