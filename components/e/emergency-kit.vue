<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0py8_4ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-kit" /></template>
<style>
.m0py8_4ym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 18H2.5V6h17v5.7M8.5 6V4A1.5 1.5 0 0 1 10 2.5h2A1.5 1.5 0 0 1 13.5 4v2M11 9v6m-3-3h6m4 2.5V18m0 3h.01");
}

</style>
