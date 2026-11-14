<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g08j9bbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arabic-script" /></template>
<style>
.g08j9bbgf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 11.75a2.75 2.75 0 1 1 5-1.5c0 6-2.75 9.5-8.25 9.5c-5 0-8-2.5-8-6.5m12-9h.01m2.99 0h.01");
}

</style>
