<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mnvp_6bsw"/><path class="nqm_75bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calorie-deficit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mnvp_6bsw {
  d: path("M8.5 19.75c-3 0-5.25-2-5.25-4.75c0-3 2.75-4.5 3.25-8c1.25 1 2 2.5 2 4c1-.5 2-1.5 2-2.5c2 1.5 3.25 3.75 3.25 6.5s-2.25 4.75-5.25 4.75");
}

.nqm_75bec {
  d: path("M8.5 19.75c-1 0-2-.75-2-1.75c0-1.5 1.25-2 2-3.5c.75 1.5 2 2 2 3.5c0 1-1 1.75-2 1.75M18.5 5v14M16 16.5l2.5 2.5l2.5-2.5");
}

</style>
