<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qbtzpkp0x"/><path class="w_5hlgbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hug" /></template>
<style>
.qbtzpkp0x {
  d: path("M14.275 17.225L12 19.5l-2.263-2.263m-4.521-4.55C2.881 9.837 4.646 4.5 8.5 4.5c1.75 0 3 1.25 3.5 2.5c.5-1.25 1.75-2.5 3.5-2.5c3.847 0 5.613 5.32 3.295 8.173");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_5hlgbaa {
  d: path("M2.5 21c1.5-4 4-6.5 6.5-6.5q1.5 0 1.5-2m11 8.5c-1.5-4-4-6.5-6.5-6.5q-1.5 0-1.5-2");
}

</style>
