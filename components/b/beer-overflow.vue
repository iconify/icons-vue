<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="je8kwq2jh"/><path class="yxfrndrbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beer-overflow" /></template>
<style>
.je8kwq2jh {
  d: path("M4 9v10.5A1.5 1.5 0 0 0 5.5 21h9a1.5 1.5 0 0 0 1.5-1.5V9m0 2h2.5a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5H16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yxfrndrbd {
  d: path("M3 13V7.5a3 3 0 0 1 4.5-3.25a3 3 0 0 1 5.5 0a3 3 0 0 1 4 3.25V9H5v4a1 1 0 0 1-2 0Z");
}

</style>
