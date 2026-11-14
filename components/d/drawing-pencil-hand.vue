<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wv276xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drawing-pencil-hand" /></template>
<style>
.z2wv276xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 15.75l1.5-4.5l8.75-8.75l3 3l-8.75 8.75Zm1.5-4.5l3 3M5 19.5c3-2.5 5 2.5 8 0s5 2 7.5 0");
}

</style>
