<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glk1z2bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boss-health" /></template>
<style>
.glk1z2bkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.5V6.914a.586.586 0 0 1 1-.414a1.058 1.058 0 0 0 1.677-.242l.073-.133a.854.854 0 0 1 1.5 0l.073.133A1.058 1.058 0 0 0 9.5 6.5a.586.586 0 0 1 1 .414V8.5A1.5 1.5 0 0 1 9 10H5a1.5 1.5 0 0 1-1.5-1.5M5.75 13h12.5a3.25 3.25 0 0 1 3.25 3.25a3.25 3.25 0 0 1-3.25 3.25H5.75a3.25 3.25 0 0 1-3.25-3.25A3.25 3.25 0 0 1 5.75 13m-.25 3.25h10.25");
}

</style>
