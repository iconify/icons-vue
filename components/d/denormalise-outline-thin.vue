<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hy9qohbih"/><path class="v04-rubun"/><path class="c94kh66-s"/><path class="hfqua5yrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:denormalise-outline-thin" /></template>
<style>
.c94kh66-s {
  d: path("m6 9 6 6 6 -6");
}

.hfqua5yrl {
  d: path("M4 17a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hy9qohbih {
  d: path("M2 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.v04-rubun {
  d: path("M14 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
