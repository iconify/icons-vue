<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfmcf5hwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blind" /></template>
<style>
.vfmcf5hwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1.5 3.5l-2 6l3 3V21m-3-7.5l-2 4l-2.5 3m5.5-12l4 3m0 0L19 21");
}

</style>
