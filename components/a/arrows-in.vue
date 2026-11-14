<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_ud6nlgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrows-in" /></template>
<style>
.h_ud6nlgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12h.01M3.5 3.5L9 9m0-3.5V9H5.5m15-5.5L15 9m3.5 0H15V5.5m5.5 15L15 15m0 3.5V15h3.5m-15 5.5L9 15m-3.5 0H9v3.5");
}

</style>
