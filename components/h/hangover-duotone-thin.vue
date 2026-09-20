<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk5y8xrjt"/><path class="ortw0s1jo"/><path class="va8i92boq"/><path class="s55qdnbto"/><path class="fi99-bbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hangover-duotone-thin" /></template>
<style>
.fi99-bbwz {
  d: path("m15 13 -2 2");
}

.hk5y8xrjt {
  fill: currentColor;
  d: path("M5 14a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
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

.ortw0s1jo {
  d: path("M5 14a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.s55qdnbto {
  d: path("m9 13 2 2");
}

.va8i92boq {
  d: path("m7 4 2 2 3 -3 3 3 2 -2");
}

</style>
