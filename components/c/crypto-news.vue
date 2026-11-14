<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r6idl0dsj"/><path class="r92o64bxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crypto-news" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6idl0dsj {
  d: path("M4 20h15.5a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-12a2 2 0 0 0-2 2v12.5a1.5 1.5 0 0 1-3 0V10h3M9 8h9");
}

.r92o64bxq {
  d: path("M8.25 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7.75-2h2.5m-2.5 4h2.5");
}

</style>
