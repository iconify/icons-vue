<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qgavbf1rq"/><path class="yw3w9iklc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disk-clone" /></template>
<style>
.qgavbf1rq {
  d: path("M2.5 9h16v10.5h-16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yw3w9iklc {
  d: path("M5.5 9V7.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V14a2 2 0 0 1-2 2h-1M6 14.25h4.5m4.5 0h.01");
}

</style>
