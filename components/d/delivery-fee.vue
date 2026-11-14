<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vuk39w74j"/><path class="axu6y7zop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-fee" /></template>
<style>
.axu6y7zop {
  d: path("M10 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-6 7.5h16m-6-9.25v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vuk39w74j {
  d: path("M6.625 11h10.75A2.625 2.625 0 0 1 20 13.625v5.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-5.25A2.625 2.625 0 0 1 6.625 11");
}

</style>
