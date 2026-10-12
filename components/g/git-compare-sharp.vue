<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="kl-k4mbgb"/><circle class="damzbnbpb"/><path class="nbhvgmf7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-compare-sharp" /></template>
<style>
.damzbnbpb {
  cx: 17.75px;
  cy: 18.75px;
  r: 2.25px;
}

.kl-k4mbgb {
  cx: 6.25px;
  cy: 5.25px;
  r: 2.25px;
}

.nbhvgmf7b {
  d: path("M13.25 5.25h4.5V16.5m-2.5-13.25l-2 2l2 2m-4.5 11.5h-4.5V7.5m2.5 9.25l2 2l-2 2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
