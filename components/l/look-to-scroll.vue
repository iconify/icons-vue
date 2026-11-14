<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qieqmxa9v"/><path class="ph9_72b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:look-to-scroll" /></template>
<style>
.ph9_72b7u {
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM9 5l3-2.5L15 5M9 19l3 2.5l3-2.5");
}

.qieqmxa9v {
  d: path("M3.5 12c2-2.75 5-4 8.5-4s6.5 1.25 8.5 4c-2 2.75-5 4-8.5 4s-6.5-1.25-8.5-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
