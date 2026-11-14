<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fwizheqlr"/><path class="t3zcp6p6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emoji-slider" /></template>
<style>
.fwizheqlr {
  d: path("M2.5 12h3m13 0h3m-16 0a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm4.25-2h.01m4.49 0h.01");
}

.t3zcp6p6j {
  d: path("M14.815 13.625a3.25 3.25 0 0 1-5.63 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
