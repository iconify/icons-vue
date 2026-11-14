<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfvwczewd"/><path class="m7f_s8b8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-frequency" /></template>
<style>
.m7f_s8b8t {
  d: path("M15.75 5.505A7.5 7.5 0 0 1 12 19.5m-9.75-5.25L4.5 12l2.25 2.25");
}

.qfvwczewd {
  d: path("M8.25 18.495A7.5 7.5 0 0 1 12 4.5m5.25 5.25L19.5 12l2.25-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
