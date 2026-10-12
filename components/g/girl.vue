<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xn-0agmvk"/><path class="yx2bffc0c"/><circle class="o5liqyaba"/><circle class="ox23iccdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:girl" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5liqyaba {
  cx: 8.3px;
  cy: 7.6px;
  r: 1.5px;
}

.ox23iccdt {
  cx: 15.7px;
  cy: 7.6px;
  r: 1.5px;
}

.xn-0agmvk {
  cx: 12px;
  cy: 10px;
  r: 3.25px;
}

.yx2bffc0c {
  d: path("M6.5 21.25h11a.75.75 0 0 0 .75-.75c0-2.2-2.81-3.75-6.25-3.75S5.75 18.3 5.75 20.5a.75.75 0 0 0 .75.75");
}

</style>
