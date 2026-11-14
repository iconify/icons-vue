<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ovkwuobyn"/><path class="fy0oayk-g"/><path class="f7pi1hbcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hospital-elevator" /></template>
<style>
.f7pi1hbcj {
  fill: currentColor;
  d: path("M15.75 15.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.fy0oayk-g {
  d: path("M6.25 6.5L7.5 5l1.25 1.5m1.5-1.5l1.25 1.5L12.75 5m1.5 9v7.75m0-4.5h7.5V20h-7.5ZM21.5 20v1.75");
}

.ovkwuobyn {
  d: path("M11.4 19.5H2.5v-17h14v8.7M4.75 8.5h9.5m-4.75 0v11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
