<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="i5lfh_bvc"/><path class="twpk6rb8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hemisphere" /></template>
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

.i5lfh_bvc {
  d: path("M2.75 12c4.5 2.25 14 2.25 18.5 0a9.25 9.25 0 0 1-18.5 0");
}

.twpk6rb8u {
  d: path("M4.22 7c4.5 2 11.06 2 15.56 0M12 2.75c-2.5 2.5-3.75 5.6-3.75 10.4");
}

</style>
