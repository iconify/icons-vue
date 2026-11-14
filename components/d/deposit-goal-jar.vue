<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9_n-kk0b"/><path class="fdvdmcjud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-goal-jar" /></template>
<style>
.fdvdmcjud {
  d: path("M7.5 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.5-4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9_n-kk0b {
  d: path("M7.75 5.5h8.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 16.25 8h-8.5A1.25 1.25 0 0 1 6.5 6.75A1.25 1.25 0 0 1 7.75 5.5M7 8h10c1.5 1.5 2 3 2 4.5V19a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19v-6.5c0-1.5.5-3 2-4.5m7.5-2.5V2m1.193.373l.807.252a.655.655 0 0 1 0 1.25l-.807.252A.92.92 0 0 1 14.5 3.25a.92.92 0 0 1 1.193-.877");
}

</style>
