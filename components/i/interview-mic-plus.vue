<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds_-fruvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interview-mic-plus" /></template>
<style>
.ds_-fruvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 21.5c0-4 3-6.25 6.5-6.25c1.246 0 2.428.285 3.434.833M17.75 3za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 17.75 9A1.75 1.75 0 0 1 16 7.25v-2.5A1.75 1.75 0 0 1 17.75 3m0 6v3m.25 3v6m-3-3h6");
}

</style>
