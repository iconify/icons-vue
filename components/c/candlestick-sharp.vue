<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btipolb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candlestick-sharp" /></template>
<style>
.btipolb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7.75h3.5v8.5h-3.5zm1.75-3.5v3.5m0 8.5v3.5m4.75-14.5h3.5v7h-3.5zM12 2.75v2.5m0 7v4m4.75-6h3.5v7.5h-3.5zm1.75-3.5v3.5m0 7.5v3.5");
}

</style>
