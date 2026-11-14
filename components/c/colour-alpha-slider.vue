<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv8ggs65g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-alpha-slider" /></template>
<style>
.qv8ggs65g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h6v6h-6Zm3 0v6m-3-3h6m2.75 0h2.5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0h2.75");
}

</style>
