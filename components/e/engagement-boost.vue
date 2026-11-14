<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6-fg9bkr"/><path class="tds05_giu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engagement-boost" /></template>
<style>
.h6-fg9bkr {
  d: path("M20.5 3.5C16 3.5 12.5 6 10 10l4 4c4-2.5 6.5-6 6.5-10.5Z");
}

.tds05_giu {
  d: path("M10.5 9.5H7L4.5 12H8m6.5 1.5V17L12 19.5V16m2.5-8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM5 15h4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
