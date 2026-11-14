<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2mok5b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-box-plot" /></template>
<style>
.r2mok5b5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4v4.5m-.375 0h.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 7.875 15.5h-.75A2.625 2.625 0 0 1 4.5 12.875v-1.75A2.625 2.625 0 0 1 7.125 8.5m.375 7V20m9-16v2.5m-.375 0h.75A2.625 2.625 0 0 1 19.5 9.125v.75a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 13.5 9.875v-.75A2.625 2.625 0 0 1 16.125 6.5m.375 6V17m-12-5h6m3-2h6");
}

</style>
