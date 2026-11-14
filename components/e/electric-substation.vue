<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wirkudc-w"/><path class="ftuhgq31z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-substation" /></template>
<style>
.ftuhgq31z {
  d: path("M9.75 11.25L7 15h3l-2.75 3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wirkudc-w {
  d: path("M6.125 8.5h4.75a2.625 2.625 0 0 1 2.625 2.625v7.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 3.5 18.875v-7.75A2.625 2.625 0 0 1 6.125 8.5M18 21.5V4m-2.5 1.5h5m-18 16h19");
}

</style>
