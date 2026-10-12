<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-_703bau"/><circle class="ons53cb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kubernetes-wheel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.v-_703bau {
  d: path("m13.58 3.26l4.27 2.06q1.58.76 1.97 2.46l1.05 4.63q.39 1.7-.7 3.07l-2.96 3.71q-1.09 1.37-2.84 1.37H9.63q-1.75 0-2.84-1.37l-2.96-3.71q-1.09-1.37-.7-3.07l1.05-4.63q.39-1.7 1.97-2.46l4.27-2.06q1.58-.76 3.16 0M12 8.25V5m2.93 4.66l2.54-2.02m-1.81 5.19l3.16.73m-5.19 1.82l1.41 2.93m-4.67-2.93l-1.41 2.93m-.62-5.48l-3.16.73m3.89-3.9L6.53 7.64");
}

</style>
