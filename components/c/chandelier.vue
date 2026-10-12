<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-_gsncpq"/><circle class="vtw09psrf"/><path class="m60agcc_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chandelier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m60agcc_b {
  d: path("M12 17.75v2.5M4.75 11V8.75M19.25 11V8.75M8.5 14.25V11.5m7 2.75V11.5M4.75 4C5.5 4.7 6 5.35 6 6a1.25 1.25 0 0 1-2.5 0c0-.65.5-1.3 1.25-2m14.5 0c.75.7 1.25 1.35 1.25 2A1.25 1.25 0 0 1 18 6c0-.65.5-1.3 1.25-2M8.5 6.75c.75.7 1.25 1.35 1.25 2a1.25 1.25 0 0 1-2.5 0c0-.65.5-1.3 1.25-2m7 0c.75.7 1.25 1.35 1.25 2a1.25 1.25 0 0 1-2.5 0c0-.65.5-1.3 1.25-2");
}

.vtw09psrf {
  cx: 12px;
  cy: 16.25px;
  r: 1.5px;
}

.z-_gsncpq {
  d: path("M10 2.75h4m-2 0v12M4.75 11c0 2.5 3 3.75 7.25 3.75s7.25-1.25 7.25-3.75m-16 0h3m11.5 0h3");
}

</style>
