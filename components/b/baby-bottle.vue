<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st0ouozjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-bottle" /></template>
<style>
.st0ouozjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6V3.5a1.5 1.5 0 0 1 3 0V6M10 6h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 14 9h-4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 10 6m1.875 3h.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 12.125 21h-.25A4.375 4.375 0 0 1 7.5 16.625v-3.25A4.375 4.375 0 0 1 11.875 9M10 13h2.5M10 16.5h2.5");
}

</style>
