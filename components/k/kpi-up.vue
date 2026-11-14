<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j9hmn46zr"/><path class="xhvwhd-up"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-up" /></template>
<style>
.j9hmn46zr {
  d: path("M2.5 4.5h19v15h-19ZM6 9h4m-4 5.5h4m5.5 1v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhvwhd-up {
  d: path("m13 11l2.5-2.5L18 11");
}

</style>
