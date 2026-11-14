<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-m47t2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-tree" /></template>
<style>
.k_-m47t2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 21.5l1-9.5L6.5 8L6 3.5m8.75 18l-1-9.5L16 7l4-2.5M16 7l-.5-4m-1.25 13.5l2.75-2m-11.5 7h13");
}

</style>
