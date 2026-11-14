<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mat3r6bby"/><path class="o6cfftb7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barcode-sticker-roll" /></template>
<style>
.mat3r6bby {
  d: path("M2.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 4h15");
}

.o6cfftb7z {
  d: path("M5.25 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm7-2H16v6h-3.75Zm5.5 0h3.75v6h-3.75ZM14 12v2m5.5-2v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
