<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wtg96uwoc"/><path class="sawgdkbmg"/><rect class="rc5eupb5p"/><rect class="rdaoyeb6x"/><rect class="wzr4ge67z"/><rect class="u1bri2b1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:attention-map" /></template>
<style>
.rc5eupb5p {
  width: 3.75px;
  height: 3.75px;
  x: 10.75px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.rdaoyeb6x {
  width: 3.75px;
  height: 3.75px;
  x: 17.5px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.sawgdkbmg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 6.5h.01");
}

.u1bri2b1s {
  width: 3.75px;
  height: 3.75px;
  x: 17.5px;
  y: 17.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.wtg96uwoc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5q4.75-6.5 9.5 0q-4.75 6.5-9.5 0");
}

.wzr4ge67z {
  width: 3.75px;
  height: 3.75px;
  x: 10.75px;
  y: 17.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
