<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4c13hb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-ohlc" /></template>
<style>
.a4c13hb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5V17m7-14v12m7-7v13M2.75 8H5m0 6h2.25m2.5-2H12m0-6.5h2.25m2.5 5.5H19m0 7h2.25");
}

</style>
