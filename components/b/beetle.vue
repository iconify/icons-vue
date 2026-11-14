<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3idvoqgd"/><path class="k-qlf2bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beetle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-qlf2bfn {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 9v11.5M7.25 10L4 7.5M6.5 14H3m4.75 4L4.5 21m12.25-11L20 7.5M17.5 14H21m-4.75 4l3.25 3");
}

.y3idvoqgd {
  d: path("M6.5 13.5a5.5 7 0 1 0 11 0a5.5 7 0 1 0-11 0");
}

</style>
