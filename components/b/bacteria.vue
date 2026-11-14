<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qg_9qbcun"/><path class="ra17x9b1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bacteria" /></template>
<style>
.qg_9qbcun {
  d: path("m6.518 5.72l8.192 5.736a1.25 1.25 0 0 1 .307 1.741l-2.294 3.276a1.25 1.25 0 0 1-1.741.307L2.79 11.044a1.25 1.25 0 0 1-.307-1.741l2.294-3.276a1.25 1.25 0 0 1 1.741-.307ZM7 10h.01m3.49 2.5h.01");
}

.ra17x9b1a {
  d: path("M13.5 15c2 .75 1.25 2.75 3.25 3.5s2 2.5 4.75 3M14.25 14c2.25 0 2.25-1.5 4.25-1.25c1.5.25 2.25 1.5 3 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
