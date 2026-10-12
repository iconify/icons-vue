<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sreeq_hqq"/><circle class="rip_g9cqu"/><path class="upfrolbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battle-axe" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rip_g9cqu {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

.sreeq_hqq {
  d: path("M12 2.75v14.5");
}

.upfrolbgt {
  d: path("M12 7.75h2q2-.5 4-3.5q4.5 5.75 0 11.5q-2-3-4-3.5h-2Zm0 0h-2q-2-.5-4-3.5Q1.5 10 6 15.75q2-3 4-3.5h2Z");
}

</style>
