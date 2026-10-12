<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gn1q4_bxc"/><path class="jqha4tb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitchen-island-sharp" /></template>
<style>
.gn1q4_bxc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v3.5H2.75zm2 6h14.5v9H4.75v-2Zm7.25 0v9");
}

.jqha4tb8j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 14.75h.01m3.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
