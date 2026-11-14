<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7e4f556u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-sankey" /></template>
<style>
.b7e4f556u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6v12m17-15.5V6m0 10v5.5M3.5 6c8.5 0 8.5-3.5 17-3.5m-17 7C12 9.5 12 6 20.5 6m-17 6.5c8.5 0 8.5 3.5 17 3.5m-17 2c8.5 0 8.5 3.5 17 3.5");
}

</style>
