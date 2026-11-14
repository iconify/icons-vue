<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn-518zch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:improvement-plan" /></template>
<style>
.xn-518zch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 21.5h20m-19.5-10C5 11.5 6 15 9 15s5-5 8.25-7.25m0 0V2.5m0 0l3.5 2l-3.5 2");
}

</style>
