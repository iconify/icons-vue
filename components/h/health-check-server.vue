<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cys7ydbni"/><path class="fkcg0w6by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-check-server" /></template>
<style>
.cys7ydbni {
  d: path("M6 3h10a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 16 15H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 3");
}

.fkcg0w6by {
  d: path("M5.5 9H8l1.5-3l2 6L13 9h3m-1.25 9l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
