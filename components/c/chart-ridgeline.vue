<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph_plk_zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-ridgeline" /></template>
<style>
.ph_plk_zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8C6 8 7 4.5 9.5 4.5S13 8 20.5 8m-17 6C7 14 8 10 11 10s4 4 9.5 4m-17 6C8 20 9 16 13 16c3 0 4 4 7.5 4");
}

</style>
