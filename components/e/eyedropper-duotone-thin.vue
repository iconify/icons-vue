<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ie2d97bxq"/><path class="yh9u3ugmc"/><path class="zcnxk5bij"/><path class="mycgd0b6x"/><path class="vdktr42cl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eyedropper-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie2d97bxq {
  fill: currentColor;
  d: path("M13 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mycgd0b6x {
  d: path("m14 9 -7 7");
}

.vdktr42cl {
  d: path("M3.5 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yh9u3ugmc {
  fill: currentColor;
  d: path("M3.5 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zcnxk5bij {
  d: path("M13 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
