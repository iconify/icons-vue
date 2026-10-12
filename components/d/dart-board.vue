<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xh4evtb-j"/><circle class="r0n4bnoau"/><path class="doltwk4-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dart-board" /></template>
<style>
.doltwk4-b {
  d: path("M12.5 13.5h5.75m-9.75 0H2.75m7.75 2v5.75m0-9.75V5.75m0 7.75l8-8m-2.25-1.25v3.5h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0n4bnoau {
  cx: 10.5px;
  cy: 13.5px;
  r: 4.75px;
}

.xh4evtb-j {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.75px;
}

</style>
