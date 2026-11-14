<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq3bkfi4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kipps-apparatus" /></template>
<style>
.iq3bkfi4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 6.5a2 2 0 1 1 0-4a2 2 0 1 1 0 4V9a3 3 0 1 1 0 6a3 3 0 1 1 0-6m0 6v1a5.5 2.75 0 1 1 0 5.5a5.5 2.75 0 1 1 0-5.5m3-4H19m0-1.5v3");
}

</style>
