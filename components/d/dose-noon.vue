<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hryqq76ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-noon" /></template>
<style>
.hryqq76ol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5h13V19h-13ZM3 21h18M9 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-5 0h2m12 0h2M8.25 3.75l-1-1m8.5 1l1-1");
}

</style>
