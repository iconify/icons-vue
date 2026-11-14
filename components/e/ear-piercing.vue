<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="avipjbcle"/><path class="rnju_bbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ear-piercing" /></template>
<style>
.avipjbcle {
  d: path("M6.5 8.5c0-3.75 2.5-6 5.5-6c3.25 0 5.5 2.5 5.5 6c0 3-2 4.5-3.5 6c-1 1-1 2.5-1 3.5c0 2-1.5 3.5-3.5 3.5c-1.5 0-2.5-1-3-2");
}

.rnju_bbji {
  d: path("M9.5 9c0-2 1-3 2.5-3s2.5 1 2.5 2.5S13 11 12 12m-2.25 6h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
