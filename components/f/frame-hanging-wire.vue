<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmvbv6boj"/><path class="fgypfbc5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frame-hanging-wire" /></template>
<style>
.fgypfbc5b {
  d: path("m6 18l3.5-3.5l3 2.25L15 14.5l3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmvbv6boj {
  d: path("M5.125 10h13.75a2.625 2.625 0 0 1 2.625 2.625v5.75A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375v-5.75A2.625 2.625 0 0 1 5.125 10M8.5 10L12 4.5l3.5 5.5M12 2.5v2");
}

</style>
