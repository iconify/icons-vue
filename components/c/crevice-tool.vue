<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n498jz1nm"/><path class="rbydfgbqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crevice-tool" /></template>
<style>
.n498jz1nm {
  d: path("m16.596 5.99l3.182.353l-8.485 9.9l-3.536-3.536Z");
}

.rbydfgbqf {
  d: path("M7.05 12L12 16.95l-4.243 4.242l-4.949-4.949Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
