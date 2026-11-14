<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zx9538bop"/><path class="g0xgncckz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-cream-truck" /></template>
<style>
.g0xgncckz {
  d: path("M4.5 20a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9 10L5.5 6h7ZM5.5 6a3.5 3.5 0 0 1 7 0M5 12.75h6.5v2.75H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zx9538bop {
  d: path("M2.5 18v-6.5A1.5 1.5 0 0 1 4 10h10a1.5 1.5 0 0 1 1.5 1.5V13h3l3 3v2Z");
}

</style>
