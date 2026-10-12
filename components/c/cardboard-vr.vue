<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bptykd5pb"/><circle class="q37snoy7l"/><circle class="s33wmo_6g"/><rect class="yxnr6lryx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cardboard-vr" /></template>
<style>
.bptykd5pb {
  d: path("M4.25 7.5h15.5a1.5 1.5 0 0 1 1.5 1.5v8.5a1.5 1.5 0 0 1-1.5 1.5H15l-1.25-4q-1.75-1.75-3.5 0L9 19H4.25a1.5 1.5 0 0 1-1.5-1.5V9a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q37snoy7l {
  cx: 7.5px;
  cy: 11.75px;
  r: 1.75px;
}

.s33wmo_6g {
  cx: 16.5px;
  cy: 11.75px;
  r: 1.75px;
}

.yxnr6lryx {
  width: 10px;
  height: 4px;
  x: 7px;
  y: 3.5px;
  rx: 1px;
}

</style>
