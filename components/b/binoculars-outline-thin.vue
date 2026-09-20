<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0lu7bcgk"/><path class="mzz93ed1z"/><path class="y0y0ccsoe"/><path class="lmdddlr1e"/><path class="p7w3a5bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:binoculars-outline-thin" /></template>
<style>
.f0lu7bcgk {
  d: path("M3 8v11h7V8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmdddlr1e {
  d: path("M4 5h5");
}

.mzz93ed1z {
  d: path("M14 8v11h7V8Z");
}

.p7w3a5bcn {
  d: path("M15 5h5");
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

</style>
