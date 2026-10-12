<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z-k8j30re"/><circle class="p6d06ilmy"/><circle class="enojk2y3g"/><path class="kt42musmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:adaptive-controller" /></template>
<style>
.enojk2y3g {
  cx: 15.75px;
  cy: 12.5px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt42musmn {
  d: path("M6.5 7.25v-2.5m11 2.5v-2.5M12 7.25V5.5");
}

.p6d06ilmy {
  cx: 8.25px;
  cy: 12.5px;
  r: 2.5px;
}

.z-k8j30re {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 3px;
}

</style>
