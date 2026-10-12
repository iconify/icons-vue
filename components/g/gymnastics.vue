<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="sgjrlnbuw"/><path class="qaftagbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gymnastics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qaftagbce {
  d: path("m11.25 7.75l.75 4.5m0 0l8.75-1.75M12 12.25L3.25 13.5M11.6 10l4.65-3.25M11.6 10l-3.35-.75m-5.5 8h18.5M7 17.25v4m10-4v4");
}

.sgjrlnbuw {
  cx: 10.75px;
  cy: 4.75px;
  r: 2px;
}

</style>
