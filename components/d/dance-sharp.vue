<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9xqa_ico"/><path class="hw49njbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dance-sharp" /></template>
<style>
.e9xqa_ico {
  cx: 14px;
  cy: 4.75px;
  r: 2px;
}

.hw49njbjl {
  d: path("M13 7.5L11.5 13m1-4.25L9 7L7 3.25m5.5 5.5l3.75 1.75L19 8.75M11.5 13l4 2.5l-.75 5.75M11.5 13l-4.25 2.5l-2 3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
