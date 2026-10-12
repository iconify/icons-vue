<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="x1mm-qbte"/><path class="endw_8b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-avatar" /></template>
<style>
.endw_8b9u {
  d: path("M3.25 20.25c0-3.5 3-5.75 6.75-5.75s6.75 2.25 6.75 5.75a1 1 0 0 1-1 1H4.25a1 1 0 0 1-1-1M18.5 3.5q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1mm-qbte {
  cx: 10px;
  cy: 8px;
  r: 4.25px;
}

</style>
