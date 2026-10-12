<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxlb4ta7h"/><path class="hodpskeyj"/><rect class="dk7jol69b"/><path class="nvmpcccgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bathrobe" /></template>
<style>
.dk7jol69b {
  width: 12px;
  height: 2.25px;
  x: 6px;
  y: 11.75px;
  rx: 1px;
}

.dxlb4ta7h {
  d: path("M10 2.75h4q1.25 0 2.33.63l2.59 1.49q1.08.63 1.3 1.86l.81 4.54q.22 1.23-1 1.51l-.81.19Q18 13.25 18 14.5V20q0 1.25-1.25 1.25h-9.5Q6 21.25 6 20v-5.5q0-1.25-1.22-1.53l-.81-.19q-1.22-.28-1-1.51l.81-4.54Q4 5.5 5.08 4.87l2.59-1.49q1.08-.63 2.33-.63");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hodpskeyj {
  d: path("m9 3l3 7l3-7m-3 7v1.75");
}

.nvmpcccgo {
  d: path("m11 14l-1 3.5m3-3.5l1 3.5");
}

</style>
