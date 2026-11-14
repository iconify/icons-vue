<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="medfc4bjd"/><path class="g3uovdayt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keystone-jack" /></template>
<style>
.g3uovdayt {
  d: path("M7.5 10h9v5h-2v2h-5v-2h-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.medfc4bjd {
  d: path("m3.513 6.487l1.974-1.974A1.75 1.75 0 0 1 6.725 4h10.55a1.75 1.75 0 0 1 1.238.513l1.974 1.974A1.75 1.75 0 0 1 21 7.725V18.25A1.75 1.75 0 0 1 19.25 20H4.75A1.75 1.75 0 0 1 3 18.25V7.725a1.75 1.75 0 0 1 .513-1.238M3 7h18");
}

</style>
