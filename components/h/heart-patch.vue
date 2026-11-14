<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mdn_uib5l"/><path class="bzfticbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-patch" /></template>
<style>
.bzfticbck {
  d: path("M5.5 12h3L10 9l2.25 6l1.5-3h4.75M5.75 8.25h.01m12.49 7.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdn_uib5l {
  d: path("M8.625 5.5h6.75a6.125 6.125 0 0 1 6.125 6.125v.75a6.125 6.125 0 0 1-6.125 6.125h-6.75A6.125 6.125 0 0 1 2.5 12.375v-.75A6.125 6.125 0 0 1 8.625 5.5");
}

</style>
