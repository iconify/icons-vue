<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz7khe75n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campaign" /></template>
<style>
.qz7khe75n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h4.5l8-4.5v15l-8-4.5H3Zm4.5 6l1.25 5M18.5 9.5L21 8m-2.5 6.5L21 16");
}

</style>
