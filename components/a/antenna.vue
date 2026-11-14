<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgy_f2t6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna" /></template>
<style>
.tgy_f2t6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75a6 6 0 0 0 8.5 8.5ZM10 18v3m-3.5 0h7M15 6.25A2.75 2.75 0 0 1 17.75 9M15 3.25A5.75 5.75 0 0 1 20.75 9");
}

</style>
