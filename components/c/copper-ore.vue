<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t88qykb_q"/><path class="wgug1mb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copper-ore" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t88qykb_q {
  d: path("M3.413 12.036L5.72 6.653a1.75 1.75 0 0 1 .936-.926l4.697-1.957a1.75 1.75 0 0 1 1.301-.018l5.12 1.969a1.75 1.75 0 0 1 1.005 1.005l1.966 5.11a1.75 1.75 0 0 1-.025 1.318l-2.318 5.409a1.75 1.75 0 0 1-1.416 1.05l-7.028.781a1.75 1.75 0 0 1-1.56-.646l-4.743-5.929a1.75 1.75 0 0 1-.242-1.783");
}

.wgug1mb8j {
  d: path("M6.75 12.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5.5-3.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M13 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
