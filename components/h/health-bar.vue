<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="df37j-jsy"/><rect class="q3-s69i3m"/><rect class="nbmta4bhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:health-bar" /></template>
<style>
.df37j-jsy {
  d: path("M5.5 16.25s-2.75-2-2.75-4.75a1.6 1.6 0 0 1 2.75-1.1a1.6 1.6 0 0 1 2.75 1.1c0 2.75-2.75 4.75-2.75 4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbmta4bhn {
  width: 4px;
  height: 2.5px;
  x: 13.25px;
  y: 10.75px;
  rx: 0.75px;
}

.q3-s69i3m {
  width: 10.5px;
  height: 7.5px;
  x: 10.75px;
  y: 8.25px;
  rx: 2px;
}

</style>
