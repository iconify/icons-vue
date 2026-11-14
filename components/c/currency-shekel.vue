<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="phr86grdn"/><path class="lidid4bmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:currency-shekel" /></template>
<style>
.lidid4bmz {
  d: path("M18.5 4.5v15h-6A3.5 3.5 0 0 1 9 16V9");
}

.phr86grdn {
  d: path("M5.5 19.5v-15h6A3.5 3.5 0 0 1 15 8v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
