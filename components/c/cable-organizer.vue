<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-8qbonqc"/><rect class="f0qzv3b8g"/><path class="fc-nje54a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cable-organizer" /></template>
<style>
.e-8qbonqc {
  d: path("M7.5 12.75V8C7.5 6 6 4.5 4 2.75m8 10v-10m4.5 10V8c0-2 1.5-3.5 3.5-5.25");
}

.f0qzv3b8g {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 12.75px;
  rx: 2px;
}

.fc-nje54a {
  d: path("M6.75 17h10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
