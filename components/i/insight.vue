<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffw-mq63t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insight" /></template>
<style>
.ffw-mq63t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17v-1.5c-2-1.2-3.5-3.3-3.5-6a6.5 6.5 0 0 1 13 0c0 2.7-1.5 4.8-3.5 6V17Zm.5 3.5h5M10 12v-1.5m2 1.5V8m2 4V9.5");
}

</style>
