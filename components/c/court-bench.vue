<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e9-7-8-2z"/><path class="pvtcqo3jc"/><rect class="u_1-4syze"/><rect class="kh4ob9bst"/><path class="ehccj3bat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:court-bench" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.ehccj3bat {
  d: path("M8 16.75h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh4ob9bst {
  width: 15.5px;
  height: 8.5px;
  x: 4.25px;
  y: 12.75px;
  rx: 1px;
}

.pvtcqo3jc {
  d: path("M8.5 10.25a3.5 3.5 0 0 1 7 0Z");
}

.u_1-4syze {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 10.25px;
  rx: 1px;
}

</style>
