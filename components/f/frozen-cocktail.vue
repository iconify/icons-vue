<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv4eh-2mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frozen-cocktail" /></template>
<style>
.hv4eh-2mf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h14a7 5.5 0 0 1-14 0Zm.5 0A3 3 0 0 1 8 7a4 4 0 0 1 8 0a3 3 0 0 1 2.5 4M12 16.5v4m-3.5 0h7");
}

</style>
