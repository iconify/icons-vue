<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c__xnac5i"/><path class="nzqy8b1bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-installation" /></template>
<style>
.c__xnac5i {
  d: path("M4.75 5h5.5A1.75 1.75 0 0 1 12 6.75v7.5A1.75 1.75 0 0 1 10.25 16h-5.5A1.75 1.75 0 0 1 3 14.25v-7.5A1.75 1.75 0 0 1 4.75 5m12 0h3a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 13h-3A1.75 1.75 0 0 1 15 11.25v-4.5A1.75 1.75 0 0 1 16.75 5M2.5 19.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzqy8b1bz {
  d: path("M5.75 13.25L8 9.5L9.25 11");
}

</style>
