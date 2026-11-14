<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o35hqiawg"/><path class="wyli5loxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:homeowner-insurance" /></template>
<style>
.o35hqiawg {
  d: path("M2.5 11a9.5 8 0 0 1 19 0q-2.25-1.5-4.5 0q-2.5-1.5-5 0q-2.5-1.5-5 0q-2.25-1.5-4.5 0ZM7 16l5-3.75L17 16v5.5H7Zm5-5.25v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyli5loxo {
  d: path("M10.5 21.5v-3h3v3");
}

</style>
