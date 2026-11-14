<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un-vgvhjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interchange" /></template>
<style>
.un-vgvhjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H8m8 0h5.5m-17 7.5l4.75-4.75m5.5-5.5L19.5 4.5M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
