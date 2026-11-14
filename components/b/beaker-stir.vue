<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbszi-bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beaker-stir" /></template>
<style>
.mbszi-bur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3H7v15.5A2.5 2.5 0 0 0 9.5 21h5a2.5 2.5 0 0 0 2.5-2.5V3h1.5M7 13h10M15.5 2.5l-4 12.5");
}

</style>
