<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ggpe1_b2k"/><path class="pmua0m53g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chalk-line" /></template>
<style>
.ggpe1_b2k {
  width: 10.5px;
  height: 10px;
  x: 2.75px;
  y: 8.5px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmua0m53g {
  d: path("M6 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-5v-3H5m8.25 8h5.5m0-2.25v4.5h2.5m-7.5 3h1.5m1.75 0h1.5m1.5 0h1.25");
}

</style>
