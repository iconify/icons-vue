<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf5q3cbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:link-building" /></template>
<style>
.gf5q3cbzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12l-3 3a3.5 3.5 0 0 0 5 5l3-3m0-10l3-3a3.5 3.5 0 0 1 5 5l-3 3m-8.25 3.25l6.5-6.5M18 15v6m-3-3h6");
}

</style>
