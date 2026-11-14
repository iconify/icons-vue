<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md2g9nvaz"/><path class="ytm6ze8qg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:highlight-color" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md2g9nvaz {
  d: path("m6 15l6-12l6 12m-9.75-4.5h7.5");
}

.ytm6ze8qg {
  fill: currentColor;
  d: path("M7.5 18h9a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19.5A1.5 1.5 0 0 1 7.5 18");
}

</style>
