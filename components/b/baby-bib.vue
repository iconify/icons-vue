<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cbb4czaic"/><path class="hynql4b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-bib" /></template>
<style>
.cbb4czaic {
  d: path("M8.25 3.75a3.75 3.75 0 0 0 7.5 0h.5A4 4 0 0 1 19.75 8v5.5a7.75 7.75 0 0 1-15.5 0V8a4 4 0 0 1 3.5-4.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hynql4b9d {
  d: path("M8.5 15.25c1 1.5 2.25 2.25 3.5 2.25s2.5-.75 3.5-2.25");
}

</style>
