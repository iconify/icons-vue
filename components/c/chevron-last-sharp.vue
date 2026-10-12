<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kjm_8kbdd"/><path class="x7mmjacnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chevron-last-sharp" /></template>
<style>
.kjm_8kbdd {
  d: path("M5.5 5.25L12.25 12L5.5 18.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7mmjacnf {
  d: path("M11.75 5.25L18.5 12l-6.75 6.75");
}

</style>
