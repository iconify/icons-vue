<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="p4y0o94ut"/><path class="sfq36tbjo"/><rect class="zvbx2cc1y"/><path class="bbfecwvte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-week" /></template>
<style>
.bbfecwvte {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17.5h.01m3.99 0h.01m3.99 0h.01");
}

.p4y0o94ut {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.sfq36tbjo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zvbx2cc1y {
  width: 10.5px;
  height: 2.5px;
  x: 6.75px;
  y: 12.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

</style>
