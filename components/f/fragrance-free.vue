<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cynn8-igd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fragrance-free" /></template>
<style>
.cynn8-igd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.6 21.5H5.5V10h.6m7.8 0h4.6v4.6M9 5.1V4h6v6h-1.1M3.5 3.5l17 17");
}

</style>
