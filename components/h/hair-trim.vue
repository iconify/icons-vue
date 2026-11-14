<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hosf15bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-trim" /></template>
<style>
.hosf15bjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 9l9 7.5M7 15l9-7.5m3.5-5c-2 4 2 8 0 12.5m-2 6.5l2-6.5l2 6.5");
}

</style>
