<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm-jz4b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infrared-thermometer-lab" /></template>
<style>
.xm-jz4b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h11v5.5h-5l-1 8.5H3l1-8.5H2.5Zm13.75 2.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 0h.01");
}

</style>
