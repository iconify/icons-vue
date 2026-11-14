<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_3xoxb2m"/><path class="wkz3zj77z"/><path class="ritsq9bab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crypto-exchange-rate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_3xoxb2m {
  d: path("M2.75 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M7.5 6q4.5-3.5 9 0");
}

.ritsq9bab {
  d: path("M8.25 20.5L7.5 18l2.75.25");
}

.wkz3zj77z {
  d: path("M15.75 3.5L16.5 6l-2.75-.25M16.5 18q-4.5 3.5-9 0");
}

</style>
