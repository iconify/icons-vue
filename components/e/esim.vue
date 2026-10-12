<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y---w9ofq"/><rect class="qmqdedbto"/><path class="f4mht0b2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:esim" /></template>
<style>
.f4mht0b2m {
  d: path("M6.75 15.5h6.5m1.65-9.44a3.75 3.75 0 0 1 3.04 3.04m-2.52-6a6.75 6.75 0 0 1 5.48 5.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmqdedbto {
  width: 6.5px;
  height: 5.5px;
  x: 6.75px;
  y: 12.75px;
  rx: 1px;
}

.y---w9ofq {
  d: path("M5.25 7.75h5.5q1.5 0 2.56 1.06l1.88 1.88q1.06 1.06 1.06 2.56v6.5q0 1.5-1.5 1.5h-9.5q-1.5 0-1.5-1.5V9.25q0-1.5 1.5-1.5");
}

</style>
