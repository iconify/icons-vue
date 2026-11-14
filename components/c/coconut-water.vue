<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8-33f5qx"/><path class="skqwaecuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coconut-water" /></template>
<style>
.h8-33f5qx {
  d: path("M6 9.5c-3 3.5-2.5 12 6 12s9-8.5 6-12");
}

.skqwaecuv {
  d: path("M6 9.5a6 1.75 0 1 0 12 0a6 1.75 0 1 0-12 0Zm7 0l3.5-7M7 13q-.25 2.5.75 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
