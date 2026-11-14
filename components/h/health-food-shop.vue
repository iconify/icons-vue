<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g5xy17bcl"/><path class="vwzh8f70w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-food-shop" /></template>
<style>
.g5xy17bcl {
  d: path("m3 8l1.5-4.5h15L21 8Zm1.5 0v13h7.1m7.9-8.9V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwzh8f70w {
  d: path("M7.5 21v-6h4v6m3.5.5q0-6.75 6.75-6.75q0 6.75-6.75 6.75Zm0 0l3.25-3.25");
}

</style>
