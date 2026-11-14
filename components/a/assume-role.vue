<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3-7w2btq"/><path class="vpyrvp8lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assume-role" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3-7w2btq {
  d: path("M4 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2.5 21c0-3 1.75-5 4-5s4 2 4 5M15 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M13.5 21c0-3 1.75-5 4-5s4 2 4 5M7 5c2-2.5 8-2.5 10 0");
}

.vpyrvp8lb {
  d: path("M14.25 5H17V2.25");
}

</style>
