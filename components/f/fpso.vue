<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5-5qgbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fpso" /></template>
<style>
.e5-5qgbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19l-2 4h-15Zm2 0V9.25a2.25 2.25 0 0 1 4.5 0V12m2.75 0V9.25a2.25 2.25 0 0 1 4.5 0V12M19 12V4.5M2.5 20q2.25-2.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
