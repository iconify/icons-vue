<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ne6wphwni"/><circle class="hk4_ptb-x"/><path class="h16qlybxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ear-check" /></template>
<style>
.h16qlybxm {
  d: path("M15.75 17.5L17 18.75l2.25-2.5");
}

.hk4_ptb-x {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ne6wphwni {
  d: path("M3.75 8.25a5 5 0 0 1 10 0c0 2.75-2 4-2.75 5.5C10.25 15.5 10 18 7.25 18c-1.4 0-2.25-.75-2.6-2M6.5 8.5a2.25 2.25 0 0 1 4.5 0c0 1.25-1.25 1.75-1.75 2.75");
}

</style>
