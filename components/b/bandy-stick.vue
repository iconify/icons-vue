<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpq9apbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bandy-stick" /></template>
<style>
.kpq9apbun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 2.5L10 16c-1.5 2.5-3 4-5 4c-1.5 0-2-1.5-1-2.5m11 .5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
