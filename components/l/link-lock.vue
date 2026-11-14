<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7c9h9b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:link-lock" /></template>
<style>
.p7c9h9b3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5H7.5a4.5 4.5 0 0 0 0 9H9m6-9h1.5A4.5 4.5 0 0 1 21 10M8.5 10h7m0 6h6v4.5h-6Zm1.25 0v-1.25a1.75 1.75 0 0 1 3.5 0V16");
}

</style>
