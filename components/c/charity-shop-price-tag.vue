<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt8vzcbwd"/><path class="bhlyry-iv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-shop-price-tag" /></template>
<style>
.bhlyry-iv {
  d: path("M5.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m13 14.5l-2.75-3A2 2 0 0 1 18.5 16a2 2 0 0 1 2.75 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yt8vzcbwd {
  d: path("M5.375 2.75h3.538a2.63 2.63 0 0 1 1.856.769l4.625 4.625a2.625 2.625 0 0 1 0 3.712l-3.538 3.538a2.625 2.625 0 0 1-3.712 0l-4.625-4.625a2.63 2.63 0 0 1-.769-1.856V5.375A2.625 2.625 0 0 1 5.375 2.75");
}

</style>
