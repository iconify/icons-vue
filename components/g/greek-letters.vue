<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpv_n-b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greek-letters" /></template>
<style>
.zpv_n-b-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19.5h3.5c-2.5-2-4-5-4-8.5S7 5 12 5s7.5 2.5 7.5 6s-1.5 6.5-4 8.5H19");
}

</style>
