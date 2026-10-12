<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="wozrn6byu"/><circle class="qi3i_ebew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carbon-monoxide-alarm" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qi3i_ebew {
  cx: 15.25px;
  cy: 12px;
  r: 2.5px;
}

.wozrn6byu {
  d: path("M10.52 10.23a2.5 2.5 0 1 0 0 3.54");
}

</style>
