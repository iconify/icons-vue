<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esbve2bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:field-plot-sharp" /></template>
<style>
.esbve2bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75zm0 7.75h18.5m-9.75 0v10.75m3-18.5v7.75M6 2.75v7.75m3.25-7.75v7.75m5.5 3.25h6.5m-6.5 3.75h6.5");
}

</style>
