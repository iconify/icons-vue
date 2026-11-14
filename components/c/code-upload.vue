<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzb9v85sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-upload" /></template>
<style>
.xzb9v85sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 7l-5 5l5 5m8-10l5 5l-.233.233M14 4.5l-4 15m8 1.5v-6.5m-2.75 2.75L18 14.5l2.75 2.75");
}

</style>
