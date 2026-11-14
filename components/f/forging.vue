<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx7jtvb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forging" /></template>
<style>
.tx7jtvb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h17v2a3 3 0 0 1-3 3H15l2 3.5H7l2-3.5H8c-3 0-5-2-5.5-5Zm10-10H17v7h-4.5Zm-8 7l8-3.75");
}

</style>
