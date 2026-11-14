<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odffxlwfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:joshua-tree" /></template>
<style>
.odffxlwfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5V7m0 8c-3.5 0-6-1.5-6-5m6 2.5c3.5 0 6.5-.5 6.5-3.5M10 4.5L12 7l2-2.5M12 7V4M4 7.5L6 10l2-2.5M6 10V7m10.5-.5l2 2.5l2-2.5m-2 2.5V6M4 20.5h16");
}

</style>
