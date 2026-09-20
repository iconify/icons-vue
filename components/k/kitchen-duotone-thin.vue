<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wq-xybcpx"/><path class="bhbkaub3h"/><path class="qqfu2d8ae"/><path class="ils4s2bwq"/><path class="zugrvnb7t"/><path class="ldbufzbne"/><path class="ok9ioqb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kitchen-duotone-thin" /></template>
<style>
.bhbkaub3h {
  fill: currentColor;
  d: path("M14 3v6h7V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ils4s2bwq {
  d: path("M14 3v6h7V3Z");
}

.ldbufzbne {
  d: path("M4 13v8h16v-8");
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.qqfu2d8ae {
  d: path("M3 3v6h7V3Z");
}

.wq-xybcpx {
  fill: currentColor;
  d: path("M3 3v6h7V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
