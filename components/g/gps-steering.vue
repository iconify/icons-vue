<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rj88q-b6w"/><path class="cxfuezbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gps-steering" /></template>
<style>
.cxfuezbkl {
  d: path("M8.5 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5.5 0h5.5m4 0H18m-7.5 2V21M16 5a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rj88q-b6w {
  d: path("M3 13.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>
