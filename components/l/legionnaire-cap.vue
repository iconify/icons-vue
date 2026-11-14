<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwgh9szje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:legionnaire-cap" /></template>
<style>
.vwgh9szje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5c0-6.25 3.5-9 7.25-9s6 3 6 7.5l3.25 1.5Zm0 0L3.5 20l8-1v-5.5");
}

</style>
