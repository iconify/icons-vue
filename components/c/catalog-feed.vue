<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghbiblbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catalog-feed" /></template>
<style>
.ghbiblbiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h7v7h-7Zm10 0h7v7h-7Zm-10 10h7v7h-7Zm12 7h.01M14.5 16a3.5 3.5 0 0 1 3.5 3.5m-3.5-7a7 7 0 0 1 7 7");
}

</style>
