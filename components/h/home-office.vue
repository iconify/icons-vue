<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alqt2ccsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-office" /></template>
<style>
.alqt2ccsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h5m-2.5 0v-9l5-6m-1-3l6 2l-2.5 4Zm3.5 9h8V18h-8Zm0 5.5h8l1 3h-10Z");
}

</style>
