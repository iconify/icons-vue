<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="kbvz4dc0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-meter" /></template>
<style>
.kbvz4dc0r {
  d: path("M8.5 6h7v3h-7ZM12 18.5c-1.75 0-2.75-1.25-2.75-2.75C9.25 14 10.75 13 11 11.5c1 .75 1.5 1.5 1.5 2.5c.5-.5.75-1 1-1.75c.75 1 1.25 2.25 1.25 3.5c0 1.5-1 2.75-2.75 2.75ZM6.25 12h.01m11.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
