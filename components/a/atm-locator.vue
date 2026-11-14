<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x--30whnh"/><path class="ooo85tb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-locator" /></template>
<style>
.ooo85tb2i {
  d: path("M7 5h10v6H7Zm-.5 8.75H13m-6.25 3.5h.01m2.49 0h.01m2.49 0h.01M18 21.5c-1.75-1.75-3-3.25-3-4.75a3 3 0 0 1 6 0c0 1.5-1.25 3-3 4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x--30whnh {
  d: path("M14.3 21.5H4v-19h16v8.8");
}

</style>
