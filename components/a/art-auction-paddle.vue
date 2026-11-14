<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fg5ym7fad"/><path class="dorwbtbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-auction-paddle" /></template>
<style>
.dorwbtbpe {
  d: path("M9.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.fg5ym7fad {
  d: path("M5 2.5h14v11H5Zm5.25 11h3.5v8h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
