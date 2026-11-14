<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9cvtcqfh"/><path class="rr1q4acpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bypass-pruners" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rr1q4acpc {
  d: path("M13 11c-4 0-8 2-10.5 5.5M13 11c0 4-2 8-5.5 10.5M13 11h.01");
}

.s9cvtcqfh {
  d: path("M12.5 11.5c0-5.5 4-9 9-8.5c-4 1.5-6 5-6 8.5Zm.5-.5l8.5-2");
}

</style>
