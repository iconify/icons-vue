<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g8kpklbts"/><path class="giub7u5ak"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bus-delayed" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.g8kpklbts {
  d: path("M12 17H2.5V3.5h18v9M2.5 9h18");
}

.giub7u5ak {
  d: path("M4 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.05-1.76q-.118.064-.227.143t-.206.173q-.098.093-.182.198t-.153.221t-.121.24q-.053.124-.089.253q-.036.13-.054.264q-.018.133-.018.268q0 .162.026.322t.078.313t.127.297t.173.273t.214.241t.251.204t.28.16q.147.069.303.113M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
