<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0c575djr"/><path class="i30i2km0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cave-opening" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i30i2km0k {
  fill: currentColor;
  d: path("M7 20.5V16l2.25-3.5l3.25-1l2.75 1.5L17 16.5v4Z");
}

.o0c575djr {
  d: path("m2.5 20.5l3-9.5L9 3.5l3.5 4l2.5-1l4 5.5l2.5 8.5Z");
}

</style>
