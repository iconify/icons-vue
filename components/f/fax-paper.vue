<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t4_9k-bwm"/><path class="i0mkkg3-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fax-paper" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0mkkg3-z {
  d: path("M17 6a2 3 0 1 0 4 0a2 3 0 1 0-4 0M5 9v10.5l1.75 2l1.75-2l1.75 2l1.75-2l1.75 2l1.75-2V9M8 13.5h4.5");
}

.t4_9k-bwm {
  d: path("M19 3H5a2 3 0 0 0 0 6h14");
}

</style>
