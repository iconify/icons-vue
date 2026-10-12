<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rirjrmrqd"/><circle class="tubvt93bf"/><path class="ai917_bhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:action-cam" /></template>
<style>
.ai917_bhn {
  d: path("M5.75 9.25h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rirjrmrqd {
  d: path("M5.5 5.75V4.5a.75.75 0 0 1 .75-.75H8.5a.75.75 0 0 1 .75.75v1.25h9.25a2.75 2.75 0 0 1 2.75 2.75v8a2.75 2.75 0 0 1-2.75 2.75h-13a2.75 2.75 0 0 1-2.75-2.75v-8A2.75 2.75 0 0 1 5.5 5.75");
}

.tubvt93bf {
  cx: 14.5px;
  cy: 12.5px;
  r: 4px;
}

</style>
