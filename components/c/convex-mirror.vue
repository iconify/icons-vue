<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mcfo0f-ee"/><path class="zd4_f1f_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:convex-mirror" /></template>
<style>
.mcfo0f-ee {
  d: path("M21 2.5q-8 9.5 0 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd4_f1f_i {
  d: path("M3 9h14.5L9 3.5M3 15h14.5L9 20.5");
}

</style>
