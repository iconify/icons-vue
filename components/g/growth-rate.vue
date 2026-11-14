<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vp4mrabmz"/><path class="vefwv_bky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:growth-rate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vefwv_bky {
  d: path("M13.25 4.25L17 4l.75 3.75m-3 13.5l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.vp4mrabmz {
  d: path("M2.5 14.5c4 0 7 0 9-2.5L17 4");
}

</style>
