<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ed0_x-bie"/><path class="hn590nbph"/><path class="qqda0pg3j"/><path class="c520s6bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-bus" /></template>
<style>
.c520s6bog {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9.75v2.5h2.5l.75 2m-4.85-3.4a2.25 2.25 0 1 0 3 3.25M14 8h4.25M14 8v6");
}

.ed0_x-bie {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.hn590nbph {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.25a2.5 2.5 0 0 0 5 0m4.5 0a2.5 2.5 0 0 0 5 0");
}

.qqda0pg3j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
