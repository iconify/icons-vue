<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r50l4xbjd"/><path class="jor4g7drs"/><path class="x5p_dkb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coin-swap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jor4g7drs {
  d: path("M17.25 7.75L19 9.5l1.75-1.75M9.5 19.5H7a2 2 0 0 1-2-2v-3");
}

.r50l4xbjd {
  d: path("M2.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m10 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m2-12.5H17a2 2 0 0 1 2 2v3");
}

.x5p_dkb2k {
  d: path("M3.25 16.25L5 14.5l1.75 1.75");
}

</style>
