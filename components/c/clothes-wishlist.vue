<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cixudtbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothes-wishlist" /></template>
<style>
.cixudtbof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.25A2.25 2.25 0 1 1 12 6.5m0 0l9 4.75H3Zm0 15L8 18a2.5 2.5 0 0 1 4-3a2.5 2.5 0 0 1 4 3Z");
}

</style>
