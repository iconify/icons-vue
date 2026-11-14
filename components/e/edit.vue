<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jis8zhbnz"/><path class="bsptxsbpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:edit" /></template>
<style>
.bsptxsbpy {
  d: path("m18.718 4.575l.707.707a1.5 1.5 0 0 1 0 2.122l-7.104 7.103a1.5 1.5 0 0 1-.766.41l-1.323.265a1.202 1.202 0 0 1-1.414-1.414l.265-1.323a1.5 1.5 0 0 1 .41-.766l7.103-7.104a1.5 1.5 0 0 1 2.122 0M15.182 5.99l2.828 2.828");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jis8zhbnz {
  d: path("M11 4.5H7A2.5 2.5 0 0 0 4.5 7v10A2.5 2.5 0 0 0 7 19.5h10a2.5 2.5 0 0 0 2.5-2.5v-4");
}

</style>
