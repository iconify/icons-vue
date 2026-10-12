<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rggpjjiew"/><rect class="tid5ihbau"/><path class="yt3a0mkpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-grid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rggpjjiew {
  width: 3px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

.tid5ihbau {
  width: 3px;
  height: 18.5px;
  x: 18.25px;
  y: 2.75px;
  rx: 1px;
}

.yt3a0mkpe {
  d: path("M8.75 7h6.5m-6.5 5h6.5m-6.5 5h6.5");
}

</style>
