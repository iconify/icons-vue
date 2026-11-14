<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7x2l3bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buttonhole" /></template>
<style>
.t7x2l3bsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 12a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0M17.5 5za3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3m-12 7h.01m2.99 0h.01m8.99-3.5v7");
}

</style>
