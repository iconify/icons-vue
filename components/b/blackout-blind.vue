<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3e627pou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blackout-blind" /></template>
<style>
.m3e627pou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19v3h-19Zm2 3v14A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-1.5v-14M4.5 15h15m-3 0v3.25");
}

</style>
