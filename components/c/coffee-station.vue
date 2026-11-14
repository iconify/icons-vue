<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbys-gb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-station" /></template>
<style>
.zbys-gb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h12v6a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm12 1.5h1.5a2.5 2.5 0 0 1 0 5H16M4 20h13");
}

</style>
