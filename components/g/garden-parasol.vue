<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcbzet9di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-parasol" /></template>
<style>
.rcbzet9di {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5C4 5.5 7.5 3 12 3s8 2.5 9 7.5q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0Zm9-.75V21m-4 0h8");
}

</style>
