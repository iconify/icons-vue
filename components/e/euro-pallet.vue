<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4bfr8b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:euro-pallet" /></template>
<style>
.w4bfr8b0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19v4h-19Zm0 6h19v3h-19ZM5 12v2m7-2v2m7-2v2M5 17v3.5m7-3.5v3.5m7-3.5v3.5");
}

</style>
