<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvgf8wtwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-tools" /></template>
<style>
.jvgf8wtwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 4.5A4.5 4.5 0 0 0 10 10l-6.5 6.5a2 2 0 0 0 4 4L14 14a4.5 4.5 0 0 0 5.5-4.5l-3 3l-4-4Z");
}

</style>
