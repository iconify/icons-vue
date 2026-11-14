<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bbkdi9baw"/><path class="s_2cqnbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guest-add" /></template>
<style>
.bbkdi9baw {
  d: path("M5.75 7.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M3 21c0-4 3-6.25 7-6.25q2.25 0 3.75.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_2cqnbxn {
  d: path("M7.75 14.75L10 17.5l2.25-2.75M18 15v6m-3-3h6");
}

</style>
