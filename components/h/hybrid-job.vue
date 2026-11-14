<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2k4lcbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hybrid-job" /></template>
<style>
.h2k4lcbgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 19v-5.5a1 1 0 0 1 2 0V11a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v2.5a1 1 0 0 1 2 0V19Zm1.5 0v2m7.5-2v2m-9-5.25h10.5M18.75 4a1.375 1.375 0 0 1 2.75 0v9a1.25 1.25 0 0 1-1.25 1.25H16.5A1.25 1.25 0 0 1 15.25 13a1.25 1.25 0 0 1 1.25-1.25h2.25Zm-.5 10.25V17m-3 2l3-2l3 2m-6 2.75h.01m5.99 0h.01");
}

</style>
