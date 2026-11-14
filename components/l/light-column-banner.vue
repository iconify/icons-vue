<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4dcpgur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-column-banner" /></template>
<style>
.tk4dcpgur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6h5L9.25 2.5h-2.5ZM8 6v15.5m-2.5 0h5M8 9h10m-7 0v10l3.5-2.5L18 19V9");
}

</style>
