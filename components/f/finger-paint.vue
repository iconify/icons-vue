<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ji-lwpszm"/><path class="q63y-pbsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:finger-paint" /></template>
<style>
.ji-lwpszm {
  width: 11px;
  height: 9.75px;
  x: 6.25px;
  y: 11.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4.5px;
}

.q63y-pbsz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9.25V7.5m3 1.25v-4m3 4V4m3 5.25V6m3.25 9.25l.75-2.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
