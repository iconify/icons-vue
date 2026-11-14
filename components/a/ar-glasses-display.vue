<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubiciovmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ar-glasses-display" /></template>
<style>
.ubiciovmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5za4 4 0 0 1 4 4v1a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-1a4 4 0 0 1 4-4m11 0za4 4 0 0 1 4 4v1a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-1a4 4 0 0 1 4-4m-7 3q1.5-1.5 3 0m3 1.25h2.25");
}

</style>
