<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iro51zd1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-cream" /></template>
<style>
.iro51zd1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9.25a6.25 6.25 0 0 1 12.5 0A1.25 1.25 0 0 1 17 10.5H7a1.25 1.25 0 0 1-1.25-1.25M7 12.75h10l-4.25 7.5a.85.85 0 0 1-1.5 0Zm3.75 2.75h2.5");
}

</style>
