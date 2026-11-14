<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="wm_0e3b_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:influencer-contract" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.wm_0e3b_k {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 7h2.75M8 11h6.25M8 16.75c1.25-3 2.75-2.75 2.5-.5c-.25 1 1.75-2.25 2.75-.75c.5.75 1.5.5 2.75-.25M8 19h8");
}

</style>
