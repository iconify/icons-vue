<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwi8jj3lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:julep-strainer" /></template>
<style>
.uwi8jj3lg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm-4.5 0H7m4.25-2.5v5m2.75-6v7m2.75-6v5");
}

</style>
