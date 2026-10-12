<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qu3-hqbsn"/><circle class="s2aba_b7h"/><rect class="pf5_pbj3q"/><rect class="weciplc9o"/><path class="vj6gb6bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coworking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pf5_pbj3q {
  width: 6px;
  height: 5.5px;
  x: 4.25px;
  y: 9.5px;
  rx: 1px;
}

.qu3-hqbsn {
  cx: 7.25px;
  cy: 4.75px;
  r: 1.75px;
}

.s2aba_b7h {
  cx: 16.75px;
  cy: 4.75px;
  r: 1.75px;
}

.vj6gb6bph {
  d: path("M2.75 15h18.5m-16 0v6.25M18.75 15v6.25");
}

.weciplc9o {
  width: 6px;
  height: 5.5px;
  x: 13.75px;
  y: 9.5px;
  rx: 1px;
}

</style>
