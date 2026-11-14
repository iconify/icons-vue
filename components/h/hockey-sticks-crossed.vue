<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xziko6bwu"/><path class="u1g90la5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-sticks-crossed" /></template>
<style>
.u1g90la5o {
  d: path("M6 3.5L16 19q1 1.5 3 1.5h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xziko6bwu {
  d: path("M18 3.5L8 19q-1 1.5-3 1.5H3");
}

</style>
