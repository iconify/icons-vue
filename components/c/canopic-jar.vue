<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7pzvbbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canopic-jar" /></template>
<style>
.a7pzvbbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9c-3.5 2-3.5 9 0 12h10c3.5-3 3.5-10 0-12Zm0 0c0-3.5 2.25-4.5 5-4.5s5 1 5 4.5m-5-6.5v2");
}

</style>
