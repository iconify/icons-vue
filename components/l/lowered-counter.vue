<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yak93r6mg"/><rect class="d1brzo6os"/><path class="pidrmzb1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lowered-counter" /></template>
<style>
.d1brzo6os {
  width: 10px;
  height: 2.5px;
  x: 11.25px;
  y: 12.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pidrmzb1u {
  d: path("M4.75 9.75v11.5m14.5-6.5v6.5m-3-18.5v5.5m-2-2l2 2l2-2");
}

.yak93r6mg {
  width: 8.5px;
  height: 2.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 1px;
}

</style>
