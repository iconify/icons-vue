<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apa2juxls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:celsius" /></template>
<style>
.apa2juxls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.5v-8a2.5 2.5 0 0 1 5 0v8a4.5 4.5 0 1 1-5 0Zm8.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9.5 9v7");
}

</style>
