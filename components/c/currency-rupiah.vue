<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="j1c1ipxpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:currency-rupiah" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1c1ipxpi {
  d: path("M6.5 16.75V7h2.25a2.5 2.5 0 0 1 0 5H6.5m2.25 0L11 16.75M13.75 19v-8.75m0 0h1.75a2.75 2.75 0 0 1 0 5.5h-1.75");
}

</style>
