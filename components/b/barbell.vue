<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tg4tituyu"/><rect class="mnl1_omsu"/><rect class="rglqq5bcx"/><rect class="c4lu4hbxh"/><path class="df4sv8b8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barbell" /></template>
<style>
.c4lu4hbxh {
  width: 2px;
  height: 7px;
  x: 18.5px;
  y: 8.5px;
  rx: 0.75px;
}

.df4sv8b8b {
  d: path("M2.75 12h.75m4.25 0h8.5m4.25 0h.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mnl1_omsu {
  width: 2.25px;
  height: 12px;
  x: 5.5px;
  y: 6px;
  rx: 1px;
}

.rglqq5bcx {
  width: 2.25px;
  height: 12px;
  x: 16.25px;
  y: 6px;
  rx: 1px;
}

.tg4tituyu {
  width: 2px;
  height: 7px;
  x: 3.5px;
  y: 8.5px;
  rx: 0.75px;
}

</style>
