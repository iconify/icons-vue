<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kl-k4mbgb"/><circle class="damzbnbpb"/><path class="ycuyecctd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-compare" /></template>
<style>
.damzbnbpb {
  cx: 17.75px;
  cy: 18.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl-k4mbgb {
  cx: 6.25px;
  cy: 5.25px;
  r: 2.25px;
}

.ycuyecctd {
  d: path("M13.25 5.25h2.5a2 2 0 0 1 2 2v9.25m-2.5-13.25l-2 2l2 2m-4.5 11.5h-2.5a2 2 0 0 1-2-2V7.5m2.5 9.25l2 2l-2 2");
}

</style>
