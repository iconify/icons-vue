<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-iev1ycj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alternate-glyph" /></template>
<style>
.y-iev1ycj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m13-6.5v11.5c0 2.5 1.25 3.5 2.75 3.5s2.25-1 2.25-2.5");
}

</style>
