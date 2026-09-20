<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enrpg0aoq"/><path class="lbted13-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handle-outline-thin" /></template>
<style>
.enrpg0aoq {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbted13-s {
  d: path("M15 12v3c0 2 3 2 4 0 2 -4 -1 -11 -7 -11 -5 0 -9 4 -9 8s4 8 9 8c2 0 3 -0.5 4 -1");
}

</style>
