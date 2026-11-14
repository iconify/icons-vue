<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr71oacge"/><path class="xu68j4rdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-loop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kr71oacge {
  d: path("M20 12.5a8 8 0 1 1-8-8");
}

.xu68j4rdt {
  d: path("M9.75 2.25L12 4.5L9.75 6.75m-1.25 3h7m-7 2.75h7m-7 2.75H13");
}

</style>
