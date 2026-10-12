<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dld8vub9v"/><path class="jrk9zqgwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:globe-desk" /></template>
<style>
.dld8vub9v {
  cx: 12px;
  cy: 8.5px;
  r: 5.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrk9zqgwq {
  d: path("M6.25 8.5h11.5M12 2.75C10.5 4.5 9.75 6.35 9.75 8.5s.75 4 2.25 5.75m0 0v2.5m-9.25 0h18.5m-16 0v4.5m13.5-4.5v4.5");
}

</style>
