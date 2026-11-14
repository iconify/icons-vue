<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="daui_1wys"/><path class="hb3-guxsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ansoff-matrix" /></template>
<style>
.daui_1wys {
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18m-6.25-2.75l3.5-3.5");
}

.hb3-guxsd {
  d: path("M15.5 5.75h2.75V8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
