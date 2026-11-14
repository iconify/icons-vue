<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ej8kbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-director" /></template>
<style>
.w5ej8kbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.75V13M18 2.75V13M6 3.5h12V7H6ZM4.5 10h15M6 13h12M6 13l12 8.5m0-8.5L6 21.5");
}

</style>
