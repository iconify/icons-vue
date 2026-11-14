<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpe1eubdh"/><path class="t6rxi1eln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-lane-leaf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t6rxi1eln {
  d: path("m5.75 9.5l2.5-6h5.25l2.25 6m-7.5-6l2.5 6l2.75-6m2 18c0-4.75 1.5-6.5 6-6.5c0 4.75-1.5 6.5-6 6.5m0 0l3.25-3.25");
}

.wpe1eubdh {
  d: path("M2.5 9.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m10 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 17h10");
}

</style>
