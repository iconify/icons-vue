<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkd-4hbny"/><path class="k4637ozip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hazmat-suit" /></template>
<style>
.k4637ozip {
  d: path("M8.75 6.5h6.5V13h-6.5ZM12 16v5.5");
}

.tkd-4hbny {
  d: path("M2.5 21.5c0-4 2-6 3.5-6.5V9.5c0-4 2.75-7 6-7s6 3 6 7V15c1.5.5 3.5 2.5 3.5 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
