<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsq4mb63t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fruit-crate" /></template>
<style>
.gsq4mb63t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19v10.5h-19Zm0 5.25h19M2.5 10A3.25 3.25 0 0 1 9 10m0 0a3.25 3.25 0 0 1 6.5 0m0 0a3.25 3.25 0 0 1 6.5 0m-9.75-3.25l1-2.5");
}

</style>
