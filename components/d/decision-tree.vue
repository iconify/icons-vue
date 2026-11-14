<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q39x4i-az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decision-tree" /></template>
<style>
.q39x4i-az {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h6v4H9Zm3 4V9m0 0l3 3l-3 3l-3-3Zm-6.5 8v-5H9m6 0h3.5v5m-16 0h6v4.5h-6Zm13 0h6v4.5h-6Z");
}

</style>
