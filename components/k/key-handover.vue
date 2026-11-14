<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2wwxhblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-handover" /></template>
<style>
.f2wwxhblg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 0H20m-3 0v3m3-3v2.5M4 19h8m-2.5-2.5L12 19l-2.5 2.5");
}

</style>
