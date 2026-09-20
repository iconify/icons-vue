<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o41x62nfc"/><path class="sxlwlmkmh"/><path class="t56w4f31r"/><path class="zbeuuub3n"/><path class="z4g4wjbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:housekeeping-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o41x62nfc {
  d: path("M4 6v12h16V6Z");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.t56w4f31r {
  d: path("M6 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z4g4wjbvf {
  d: path("M6 3h6");
}

.zbeuuub3n {
  d: path("M16 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
