<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3_jcc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:footpath-dashed" /></template>
<style>
.zi3_jcc_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 19a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0h3.5M14 19h1a3.5 3.5 0 0 0 3.5-3.5m-1-2.5a3.5 3.5 0 0 0-2.5-1h-2.75M9.5 12H9a3.5 3.5 0 0 1-3.5-3.5m1-2.5A3.5 3.5 0 0 1 9 5h2.5m2.75 0H20");
}

</style>
