<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xlccrpblu"/><path class="cenj-qwck"/><path class="omqk0r47v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:analytics-heatmap-scroll" /></template>
<style>
.cenj-qwck {
  fill: currentColor;
  d: path("M8 9.25h5.5v5.5H8Zm5.5-5.5H19v5.5h-5.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.omqk0r47v {
  d: path("M21.75 12.5v7.75m0-16.5v6");
}

.xlccrpblu {
  d: path("M5.125 3.75h11.25A2.625 2.625 0 0 1 19 6.375v11.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.625V6.375A2.625 2.625 0 0 1 5.125 3.75M8 3.75v16.5m5.5-16.5v16.5m-11-11H19m-16.5 5.5H19");
}

</style>
