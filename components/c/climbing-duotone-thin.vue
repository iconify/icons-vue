<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucf3ueb9q"/><path class="diipsobkl"/><path class="y2k1-rbcb"/><path class="win67qb0s"/><path class="ksg_s6b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:climbing-duotone-thin" /></template>
<style>
.diipsobkl {
  d: path("M5 3v18h14V3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksg_s6b5u {
  d: path("m8 16 2 2 -2 2");
}

.ucf3ueb9q {
  fill: currentColor;
  d: path("M5 3v18h14V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.win67qb0s {
  d: path("m14 11 2 2 -2 2");
}

.y2k1-rbcb {
  d: path("m8 6 2 2 -2 2");
}

</style>
