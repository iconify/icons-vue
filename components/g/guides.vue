<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lnu8_1bht"/><path class="nqv3ki-eg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guides" /></template>
<style>
.lnu8_1bht {
  d: path("M2.5 8h15M8 2.5v15");
}

.nqv3ki-eg {
  fill: currentColor;
  d: path("M21.5 5.5v5l-4-2.5Zm-16 16h5l-2.5-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
