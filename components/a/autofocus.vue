<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="td45_wziz"/><rect class="lw928mbct"/><path class="c5b24hbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autofocus" /></template>
<style>
.c5b24hbya {
  d: path("m8.5 14.25l1.75-4.5l1.75 4.5m-2.9-1.5h2.3m2.6 1.5v-4.5h2M14 12h1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lw928mbct {
  width: 12px;
  height: 9px;
  x: 6px;
  y: 7.5px;
  rx: 2px;
}

.td45_wziz {
  d: path("M2.75 7.75v-2.5a2.5 2.5 0 0 1 2.5-2.5h2.5m8.5 0h2.5a2.5 2.5 0 0 1 2.5 2.5v2.5m0 8.5v2.5a2.5 2.5 0 0 1-2.5 2.5h-2.5m-8.5 0h-2.5a2.5 2.5 0 0 1-2.5-2.5v-2.5");
}

</style>
