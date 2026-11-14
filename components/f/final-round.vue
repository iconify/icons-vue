<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiah5ccnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:final-round" /></template>
<style>
.uiah5ccnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h15v10H5Zm0 0v18.5M10 3v10m5-10v10M5 8h15M7.5 5.5h.01m9.99 0h.01m-5.01 5h.01");
}

</style>
