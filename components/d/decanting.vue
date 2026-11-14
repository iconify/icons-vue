<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g2oy38_zi"/><path class="nafmd3bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:decanting" /></template>
<style>
.g2oy38_zi {
  d: path("m11.327 7.776l-1.221-.407a1.5 1.5 0 0 1-.614-.392L6.937 4.281a1.5 1.5 0 0 0-2.503.532L3.046 8.746a1.5 1.5 0 0 0 1.58 1.99l4.025-.447a1.5 1.5 0 0 1 .679.081l1.045.38a1.424 1.424 0 0 0 1.838-.888l.063-.189a1.5 1.5 0 0 0-.949-1.897M11.25 14v1.75L7 21.5h14l-4.25-5.75V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nafmd3bkn {
  d: path("M12.25 9.75q1.75.5 1.75 2.75v4");
}

</style>
