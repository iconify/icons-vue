<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckirb2bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barcode-scanner" /></template>
<style>
.ckirb2bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5h10.5a2 2 0 0 1 2 2V10a2 2 0 0 1-2 2h-4L10 20H6l1.5-8H5a2 2 0 0 1-2-2V7.5a2 2 0 0 1 2-2Zm15 0l1.5-.75m-1.5 4h1.75M20 12l1.5.75");
}

</style>
