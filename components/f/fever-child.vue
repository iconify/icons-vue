<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dhe-nqb-j"/><path class="kyfeqdbjf"/><path class="w5573ac1r"/><path class="tupbhegqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fever-child" /></template>
<style>
.dhe-nqb-j {
  d: path("M3.5 13a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.kyfeqdbjf {
  d: path("M11.5 4.5c-.5-1.5 1.25-2 1.75-1");
}

.tupbhegqk {
  d: path("M9 13h.01M15 13h.01M10 16.5c1.25.75 2.75.75 4 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5573ac1r {
  fill: currentColor;
  d: path("M7.5 7h9v3h-9Z");
}

</style>
