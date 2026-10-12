<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olvijbcxs"/><rect class="erktun66r"/><rect class="u565dilvf"/><rect class="ho6c6od-v"/><rect class="k2jugmvcu"/><path class="hz9_1l3md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-timeline" /></template>
<style>
.erktun66r {
  width: 6px;
  height: 3.5px;
  x: 2.75px;
  y: 4px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ho6c6od-v {
  width: 4px;
  height: 3.5px;
  x: 4.75px;
  y: 10.5px;
  rx: 1.25px;
}

.hz9_1l3md {
  d: path("M11.25 2.75v13.5");
}

.k2jugmvcu {
  width: 4.75px;
  height: 3.5px;
  x: 13.75px;
  y: 10.5px;
  rx: 1.25px;
}

.olvijbcxs {
  d: path("M2.75 18.75h18.5m-15.75 0v2.5m6.5-2.5v2.5m6.5-2.5v2.5");
}

.u565dilvf {
  width: 7.5px;
  height: 3.5px;
  x: 13.75px;
  y: 4px;
  rx: 1.25px;
}

</style>
