<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bd216ac9k"/><path class="kj_dcvaoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flint" /></template>
<style>
.bd216ac9k {
  d: path("M2.5 16L6 8.5L13 7l4 5l-2 7.5L7 21Z");
}

.kj_dcvaoa {
  d: path("m6 8.5l4.5 5l4.5 6m1.5-13l2.5-3m.5 7L22 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
