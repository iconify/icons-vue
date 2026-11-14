<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cx_3m27go"/><path class="dqnr4ic9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-fee" /></template>
<style>
.cx_3m27go {
  d: path("M13.6 21.5H4v-19h16v9.6");
}

.dqnr4ic9g {
  d: path("M7 5h10v6H7Zm-.5 8.75h5.2m-4.95 3.5h.01m2.49 0h.01m5.24-2.75h4l3.25 3.25l-4 4l-3.25-3.25Zm2.25 2.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
