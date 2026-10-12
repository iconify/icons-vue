<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwb5ecpie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-and-smartwatch-sharp" /></template>
<style>
.vwb5ecpie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3h14v6h-7v5h-9V3zm-3 14.25h10m3-4h5.5v5h-5.5zm2.75 0V11.5m0 6.75V20");
}

</style>
