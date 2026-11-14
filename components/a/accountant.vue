<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzywbtvbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accountant" /></template>
<style>
.mzywbtvbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 21c0-4 3-7 7-7c.606 0 1.189.069 1.742.199M14 13h7.5v8.5H14Zm2.25 2.75h3m-3 3h.01m2.99 0h.01");
}

</style>
