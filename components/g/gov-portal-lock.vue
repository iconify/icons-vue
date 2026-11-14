<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5_d3ubsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gov-portal-lock" /></template>
<style>
.n5_d3ubsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5L12 3l9.5 5.5Zm3.5 0V20m6-11.5V20m6-11.5v3.7M2.5 20h9.7m2.8-2.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
