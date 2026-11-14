<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sctuj25ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catch-and-release" /></template>
<style>
.sctuj25ec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5c2.5-3.75 8.5-4 11.5-1l4-2.5v7l-4-2.5c-3 3-9 2.75-11.5-1Zm-1 12q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-9-7V16m-1.75-1.75L12 16l1.75-1.75");
}

</style>
