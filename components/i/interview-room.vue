<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocgtqob7z"/><path class="c9drzccss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interview-room" /></template>
<style>
.c9drzccss {
  d: path("M10 5.25za1.25 1.25 0 0 1 1.25 1.25V11A1.25 1.25 0 0 1 10 12.25A1.25 1.25 0 0 1 8.75 11V6.5A1.25 1.25 0 0 1 10 5.25m5.25 7.25h.01m-5.01 2.75h3.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-3.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocgtqob7z {
  d: path("M7.5 2.5h9A1.5 1.5 0 0 1 18 4v16a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 20V4a1.5 1.5 0 0 1 1.5-1.5m-5 19h19");
}

</style>
