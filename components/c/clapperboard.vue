<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fqspdobtc"/><rect class="p8f0y4p3y"/><path class="rs_ux8b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clapperboard" /></template>
<style>
.fqspdobtc {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8f0y4p3y {
  width: 18.5px;
  height: 4.25px;
  x: 2.75px;
  y: 3px;
  rx: 1.25px;
}

.rs_ux8b0z {
  d: path("m8.25 3l-2 4.25m7-4.25l-2 4.25m7-4.25l-2 4.25");
}

</style>
