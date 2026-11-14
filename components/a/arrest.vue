<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obl84cb6h"/><path class="otugt1b0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrest" /></template>
<style>
.obl84cb6h {
  d: path("M2.75 14.75a4 4 0 1 1 2.5 2.5m16-2.5a4 4 0 1 0-2.5 2.5");
}

.otugt1b0u {
  d: path("M4.75 6.5h3.5v3h-3.5Zm11 0h3.5v3h-3.5ZM8.25 8h7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
