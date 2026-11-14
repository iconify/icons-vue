<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl50tgu0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-candlestick-up" /></template>
<style>
.xl50tgu0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13h4.5v6h-4.5Zm7-5h4.5v6h-4.5Zm7-4h4.5v6h-4.5ZM5 10.5V13m0 6v2.5m7-16V8m0 6v2.5m7-14V4m0 6v2");
}

</style>
