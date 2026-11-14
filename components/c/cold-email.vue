<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n70xgybix"/><path class="r7gw_9_pz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-email" /></template>
<style>
.n70xgybix {
  d: path("M11.9 17H2.5V4h19v8.8");
}

.r7gw_9_pz {
  d: path("m3 5.5l9 5.75l9-5.75M18 15v6m2.598-4.5l-5.196 3m0-3l5.196 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
