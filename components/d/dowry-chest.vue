<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_gx051fv"/><path class="ri2n7c6au"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dowry-chest" /></template>
<style>
.c_gx051fv {
  d: path("M3 20V8.5a9 4 0 0 1 18 0V20Zm0-10h7m4 0h7M6.5 10v10m11-10v10");
}

.ri2n7c6au {
  d: path("M10 8h4v5.5h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
