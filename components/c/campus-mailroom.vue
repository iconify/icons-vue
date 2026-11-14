<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="en--rv-2s"/><path class="ufrklha3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campus-mailroom" /></template>
<style>
.en--rv-2s {
  d: path("M7 7h10a3.5 3.5 0 0 1 3.5 3.5v7h-17v-7A3.5 3.5 0 0 1 7 7Z");
}

.ufrklha3n {
  d: path("M10.5 17.5v-7A3.5 3.5 0 0 0 7 7m6.5 10.5v4m3-14.5V2.75m0 0h3V5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
