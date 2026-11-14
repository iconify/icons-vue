<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdtenrd_u"/><path class="b3_fxlb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glass-pipe-bend" /></template>
<style>
.b3_fxlb3q {
  d: path("M10 2.5L8.5 4v10a3.5 3.5 0 0 0 7 0V4L14 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdtenrd_u {
  d: path("M3.5 2.5L5 4v10a7 7 0 0 0 14 0V4l1.5-1.5");
}

</style>
