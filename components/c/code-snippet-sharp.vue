<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l9h7htb2s"/><path class="sue4ftoht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-snippet-sharp" /></template>
<style>
.l9h7htb2s {
  d: path("M5 2.75h15.25v18l-1.05-.67l-.65-.41L17.5 19l-1.05.67l-.65.41l-1.05.67l-1.05-.67l-.65-.41L12 19l-1.05.67l-.65.41l-1.05.67l-1.05-.67l-.65-.41L6.5 19l-1.05.67l-.65.41l-1.05.67v-18z");
}

.sue4ftoht {
  d: path("M9.75 7.25L7.5 9.75l2.25 2.5m4.5-5l2.25 2.5l-2.25 2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
