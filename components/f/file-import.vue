<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="meb583b4d"/><path class="au3bi8b4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-import" /></template>
<style>
.au3bi8b4g {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5M2.75 14.5h10m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.meb583b4d {
  d: path("M4.75 11.25v-6a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v10.5a2.5 2.5 0 0 1-2.5 2.5h-9.5a2.5 2.5 0 0 1-2.5-2.5v-1");
}

</style>
