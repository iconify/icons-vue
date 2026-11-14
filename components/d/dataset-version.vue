<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqkjrkbao"/><path class="aqfs0u-dj"/><path class="rgykehbwo"/><path class="l0tjnubeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dataset-version" /></template>
<style>
.aqfs0u-dj {
  d: path("M2.5 12.5v7a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2v-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0tjnubeg {
  d: path("M10 2.5h9.5a2 2 0 0 1 2 2V14m-19 3h13m-8-4.5v9");
}

.mqkjrkbao {
  fill: currentColor;
  d: path("M2.5 12.5v-2a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v2Z");
}

.rgykehbwo {
  d: path("M7 5.5h9.5a2 2 0 0 1 2 2V17");
}

</style>
