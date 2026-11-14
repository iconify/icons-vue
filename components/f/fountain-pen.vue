<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ps83y33yc"/><path class="wcmyxacbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fountain-pen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ps83y33yc {
  d: path("m10.641 17.087l-1.908-4.089a1.5 1.5 0 0 1-.088-1.029l1.054-3.864A1.5 1.5 0 0 1 11.146 7h1.708a1.5 1.5 0 0 1 1.447 1.105l1.054 3.864a1.5 1.5 0 0 1-.088 1.029l-1.908 4.089a1.5 1.5 0 0 1-2.718 0M12 20v-6");
}

.wcmyxacbe {
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M9.5 3.5h5");
}

</style>
