<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fwdi4jb9i"/><path class="dwozohb-m"/><rect class="dq2yo-64m"/><path class="sks2pobbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-pump" /></template>
<style>
.dq2yo-64m {
  width: 2.5px;
  height: 5px;
  x: 15.25px;
  y: 11px;
  rx: 0.75px;
}

.dwozohb-m {
  d: path("M7 9.5v8m4-8v8");
}

.fwdi4jb9i {
  width: 12.5px;
  height: 8px;
  x: 2.75px;
  y: 9.5px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sks2pobbv {
  d: path("M17.75 13.5h3.5m-15.5 4v2.75M9 17.5v2.75M19.5 3c1.15 1.5 1.75 2.55 1.75 3.4a1.75 1.75 0 0 1-3.5 0c0-.85.6-1.9 1.75-3.4");
}

</style>
