<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d4_j0zbeu"/><path class="d--8foe6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cable-hdmi" /></template>
<style>
.d--8foe6q {
  d: path("M5.25 11v2m3.25-2v2m2.5-2.25l2 .75v1l-2 .75M13 12h8");
}

.d4_j0zbeu {
  width: 8.25px;
  height: 6px;
  x: 2.75px;
  y: 9px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
