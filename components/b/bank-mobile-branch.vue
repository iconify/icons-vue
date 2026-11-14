<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aazhtnq-u"/><path class="obmftf7ng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-mobile-branch" /></template>
<style>
.aazhtnq-u {
  d: path("M5.125 9.5h13.75a2.625 2.625 0 0 1 2.625 2.625v2.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 14.875v-2.75A2.625 2.625 0 0 1 5.125 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.obmftf7ng {
  d: path("m9.25 7l1.741-1.583a1.5 1.5 0 0 1 2.018 0L14.75 7a1.437 1.437 0 0 1-.967 2.5h-3.566A1.437 1.437 0 0 1 9.25 7m-2.875 5h2.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-2.75A1.375 1.375 0 0 1 5 13.375A1.375 1.375 0 0 1 6.375 12m8.5 0h2.75A1.375 1.375 0 0 1 19 13.375a1.375 1.375 0 0 1-1.375 1.375h-2.75a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 14.875 12M5.25 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m10 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
