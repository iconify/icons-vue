<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vv5xmciin"/><path class="l0xlvxbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:advent-wreath" /></template>
<style>
.l0xlvxbjy {
  d: path("M3 9.5h2.5V14H3ZM8.25 8h2.25v4.75H8.25Zm5.25 0h2.25v4.75H13.5Zm5 1.5H21V14h-2.5ZM4.25 6.75h.01m5.24-1.5h.01m4.99 0h.01m5.24 1.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vv5xmciin {
  d: path("M2.5 16a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0Z");
}

</style>
