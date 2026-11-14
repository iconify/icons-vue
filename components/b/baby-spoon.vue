<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iuab-g5sr"/><path class="uqhq8fcoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-spoon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iuab-g5sr {
  d: path("M12.25 12.75c2.75.5 4-1.25 4.75-2.25c1.5-2 1.25-4.25-.25-5.25c-1.25-1-3.5-.5-5 1.5c-.75 1.25-1.75 3-.5 5.5Z");
}

.uqhq8fcoc {
  d: path("m11.25 12.25l-5 5.75a1.25 1.25 0 0 0 2.25 1.5l3.75-6.75");
}

</style>
