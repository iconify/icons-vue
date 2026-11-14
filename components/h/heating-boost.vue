<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onv_71shj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heating-boost" /></template>
<style>
.onv_71shj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5V5a2.5 2.5 0 0 1 5 0v8.5a4.25 4.25 0 1 1-5 0Zm12 7v-17m-3 3l3-3l3 3M8 9.5v7");
}

</style>
