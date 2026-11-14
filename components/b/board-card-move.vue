<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="goxclybyx"/><path class="yztt0wbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:board-card-move" /></template>
<style>
.goxclybyx {
  d: path("M2.5 4.2V4h19v16h-19v-5.7m6.25 0V20m6.5-16v16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yztt0wbar {
  d: path("M5 15.5h7.5m-1.217-1.217L12.5 15.5L11 17M4.5 7H11v4.5H4.5Z");
}

</style>
