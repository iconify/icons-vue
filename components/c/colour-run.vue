<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wiof_fb8w"/><path class="r3qomlq8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-run" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3qomlq8i {
  d: path("M11 15c0-2.5 2.5-4 7-4m-2.5 4c1 1.5 2.5 3 2.5 4.25a2.5 2.5 0 0 1-5 0C13 18 14.5 16.5 15.5 15");
}

.wiof_fb8w {
  d: path("M8.5 2.5q3.5 3 7 0l5 2l1 4.5l-3.5.5V15H6V9.5L2.5 9l1-4.5Z");
}

</style>
