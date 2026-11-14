<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pv0608-mj"/><path class="am8ig002k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cauliflower-ear" /></template>
<style>
.am8ig002k {
  d: path("M10 10.5C10 8 11.5 7 13 7s2.5 1.25 2.25 2.75");
}

.pv0608-mj {
  d: path("M6 9.5a4 4 0 0 1 4.25-6a4 4 0 0 1 6.25.25A4 4 0 0 1 19 9.5c0 3-3.5 4-3.5 7.5c0 2.5-1.75 4.5-4.25 4.5c-2 0-3.5-1.25-4-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
