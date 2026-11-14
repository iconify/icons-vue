<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gvdcn9bou"/><path class="iotemkbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campaign-calendar" /></template>
<style>
.gvdcn9bou {
  d: path("M11.2 20H2.5V4.5h17v7.1m-17-2.1h17M7 2.5V6m8-3.5V6");
}

.iotemkbux {
  d: path("M14 16.25h2l5.5-2.5v7.5l-5.5-2.5h-2Zm1.5 2.5l.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
