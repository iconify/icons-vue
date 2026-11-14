<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wywxn7b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angler-on-boat" /></template>
<style>
.wywxn7b5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19l-3 4h-13Zm3.75-8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8 8.75v4.75m0-3l3.5.5m-1 2L19 3m0 0v8M3 21q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
