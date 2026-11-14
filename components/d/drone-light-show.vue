<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq014e-ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-light-show" /></template>
<style>
.eq014e-ea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h5M5 2.5V6h4m6 0h4V2.5m-2.5 0h5M9 4.5h6V8H9Zm3 7q0 3.5 3.5 3.5q-3.5 0-3.5 3.5Q12 15 8.5 15q3.5 0 3.5-3.5Zm-6.5 5Q5.5 19 8 19q-2.5 0-2.5 2.5Q5.5 19 3 19q2.5 0 2.5-2.5Zm13 0q0 2.5 2.5 2.5q-2.5 0-2.5 2.5q0-2.5-2.5-2.5q2.5 0 2.5-2.5Z");
}

</style>
