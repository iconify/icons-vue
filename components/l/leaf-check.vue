<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwc54lnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-check" /></template>
<style>
.ruwc54lnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16.5c-2-8 3.5-14 14-14c0 9.5-6 15.5-14 14Zm-1.75 1.75L12.5 8.5m2.25 9.5l2 2L21 15.75");
}

</style>
