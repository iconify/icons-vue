<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oiiy8u_cj"/><path class="j68wzwbiz"/><path class="vxy4ztabh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:duffel-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j68wzwbiz {
  d: path("M8 9a4 4 0 0 1 8 0");
}

.oiiy8u_cj {
  d: path("M4 9h16a3 3 0 0 1 0 10H4A3 3 0 0 1 4 9");
}

.vxy4ztabh {
  d: path("M4 14h16");
}

</style>
