<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f2viswbeq"/><circle class="t8v__xbtr"/><path class="bxitfbcmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-revert" /></template>
<style>
.bxitfbcmh {
  d: path("M8.5 16.75h7m2.25-5v-2a4 4 0 0 0-4-4h-6.5m2.5-2.5l-2.5 2.5l2.5 2.5");
}

.f2viswbeq {
  cx: 6.25px;
  cy: 16.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t8v__xbtr {
  cx: 17.75px;
  cy: 16.75px;
  r: 2.25px;
}

</style>
