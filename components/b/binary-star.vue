<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f3ssm6bjr"/><circle class="f13673oiz"/><path class="gsl_eibwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binary-star" /></template>
<style>
.f13673oiz {
  cx: 17px;
  cy: 12px;
  r: 2.25px;
}

.f3ssm6bjr {
  cx: 7.5px;
  cy: 12px;
  r: 3.25px;
}

.gsl_eibwq {
  d: path("M4.42 6.69a9.25 9.25 0 0 1 15.59.68m.4-2.21l-.4 2.21l-2.12-.76m1.69 10.7a9.25 9.25 0 0 1-15.59-.68m-.4 2.21l.4-2.21l2.12.76");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
