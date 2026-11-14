<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-i3wyhbb"/><path class="br_el82oj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cnc-router" /></template>
<style>
.br_el82oj {
  d: path("M10.5 9v4.5l1.5 5l1.5-5V9");
}

.h-i3wyhbb {
  d: path("M2.5 15h5v3.5h9V15h5v6.5h-19Zm7-12.5h5V9h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
