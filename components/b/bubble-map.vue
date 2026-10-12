<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bu08xsbei"/><circle class="bex1-ibcs"/><circle class="sgu7b2w-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bubble-map" /></template>
<style>
.bex1-ibcs {
  cx: 9.25px;
  cy: 10.5px;
  r: 2.75px;
}

.bu08xsbei {
  d: path("m3.69 5.4l4.12-1.55q.94-.35 1.88-.02l4.62 1.59q.94.33 1.88-.02l4.12-1.55q.94-.35.94.65v12.75q0 1-.94 1.35l-4.12 1.55q-.94.35-1.88.02l-4.62-1.59q-.94-.33-1.88.02l-4.12 1.55q-.94.35-.94-.65V6.75q0-1 .94-1.35");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgu7b2w-a {
  cx: 15.5px;
  cy: 14.25px;
  r: 1.75px;
}

</style>
