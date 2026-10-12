<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g_c-f5bux"/><path class="szlljkbjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-dog" /></template>
<style>
.g_c-f5bux {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 12.25px;
  rx: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.szlljkbjv {
  d: path("M3.5 9.5h17M7 16.75l1.25-1.5l1.25 1.5l1.25-1.5l1.25 1.5l1.25-1.5l1.25 1.5l1.25-1.5l1.25 1.5");
}

</style>
