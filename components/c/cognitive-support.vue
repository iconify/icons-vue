<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pt0xs0b4g"/><path class="brdbkfzfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cognitive-support" /></template>
<style>
.brdbkfzfv {
  d: path("M10.876 7.303v-.128a.624.624 0 0 1 .624-.62a.624.624 0 0 1 .624.62v.128a.94.94 0 0 0 .469.805a.94.94 0 0 0 .931.003l.111-.064a.624.624 0 0 1 .848.231a.624.624 0 0 1-.225.85l-.11.064a.94.94 0 0 0-.463.808a.94.94 0 0 0 .463.808l.11.064a.624.624 0 0 1 .225.85a.624.624 0 0 1-.848.231l-.111-.064a.94.94 0 0 0-.931.003a.94.94 0 0 0-.469.805v.128a.624.624 0 0 1-.624.62a.624.624 0 0 1-.624-.62v-.128a.94.94 0 0 0-.469-.805a.94.94 0 0 0-.931-.003l-.111.064a.624.624 0 0 1-.848-.231a.624.624 0 0 1 .225-.85l.11-.064A.94.94 0 0 0 9.315 10a.94.94 0 0 0-.463-.808l-.11-.064a.624.624 0 0 1-.225-.85a.624.624 0 0 1 .848-.231l.111.064a.94.94 0 0 0 .931-.003a.94.94 0 0 0 .469-.805");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pt0xs0b4g {
  d: path("M8.5 21v-3.5C5.5 16 4 13 4 10c0-4.1 3.6-7.25 8-7.25c4 0 7 2.75 7.5 6.25l1.5 3.5h-1.5v3c0 1.1-.9 2-2 2h-2V21");
}

</style>
