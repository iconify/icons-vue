<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5w4_5bub"/><path class="qmqhe6bpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:free-kick" /></template>
<style>
.qmqhe6bpc {
  d: path("M16.75 7L19 9.25L21.25 7M8.5 13.25l2.25 1.5l-1 2.5h-2.5l-1-2.5Zm0 0V9.5m2.25 5.25l3.5-1m-4.5 3.5l2.25 3m-4.75-3l-2.25 3m1.25-5.5l-3.5-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5w4_5bub {
  d: path("M2.5 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm6-8.75c0-2.5 2.5-4 5.25-4c3 0 5.25 1.75 5.25 6.5");
}

</style>
