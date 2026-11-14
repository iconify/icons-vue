<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xd4thubni"/><path class="qi3-3xbtf"/><path class="f3zoati4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ab-test-winner" /></template>
<style>
.f3zoati4m {
  fill: currentColor;
  d: path("M14.5 6V3l1.75 1.75L17.5 3l1.25 1.75L20.5 3v3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qi3-3xbtf {
  d: path("m4.5 19l2-5l2 5m-3.25-1.75h2.5m8-5.75v7.25m0-7.25H18a1.75 1.75 0 0 1 0 3.5h-2.25m0 0h2.5a1.875 1.875 0 0 1 0 3.75h-2.5");
}

.xd4thubni {
  d: path("M6 12h1a3.5 3.5 0 0 1 3.5 3.5V18A3.5 3.5 0 0 1 7 21.5H6A3.5 3.5 0 0 1 2.5 18v-2.5A3.5 3.5 0 0 1 6 12m11-3.5h1a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5h-1a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 17 8.5");
}

</style>
