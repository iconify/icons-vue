<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuyqpcc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-cot" /></template>
<style>
.cuyqpcc-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19v3.5h-19Zm1.25 0c0-2.25 4.5-2.25 4.5 0M5 11.5l5 6.5m0-6.5L5 18m9-6.5l5 6.5m0-6.5L14 18");
}

</style>
