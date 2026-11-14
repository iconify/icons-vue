<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt8qh7b0u"/><path class="z1-sts18j"/><path class="mx2-bfkyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-posting" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mx2-bfkyz {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1 3.5h5m-5 2.75H13");
}

.yt8qh7b0u {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v11.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.875V6.125A2.625 2.625 0 0 1 5.125 3.5");
}

.z1-sts18j {
  d: path("M8.5 8h7A1.5 1.5 0 0 1 17 9.5v6a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 15.5v-6A1.5 1.5 0 0 1 8.5 8");
}

</style>
