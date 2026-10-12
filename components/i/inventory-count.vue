<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vijr9ibmd"/><path class="xd-vp3ztb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inventory-count" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vijr9ibmd {
  width: 15.5px;
  height: 17.5px;
  x: 4.25px;
  y: 3.75px;
  rx: 1.5px;
}

.xd-vp3ztb {
  d: path("M9 3.75v3h6v-3M9 10v7.5m3-7.5v7.5m3-7.5v7.5m-8-1.75l10-4.5");
}

</style>
