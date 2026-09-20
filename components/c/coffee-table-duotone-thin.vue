<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yde2vxf3y"/><path class="ynn2b5v5b"/><path class="s0ufku7vs"/><path class="xxgbubv3x"/><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-table-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mei2sobow {
  d: path("M19 8v12");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.s0ufku7vs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xmopbdc-t {
  d: path("M5 15h14");
}

.xxgbubv3x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yam3-1b2z {
  d: path("M5 8v12");
}

.yde2vxf3y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynn2b5v5b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
