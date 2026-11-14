<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z538azd9b"/><path class="r-d8tkevd"/><path class="mhh7m8dfc"/><path class="egv269rzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exposure-bracket" /></template>
<style>
.egv269rzj {
  d: path("M4.75 16v2.5h14.5V16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhh7m8dfc {
  fill: currentColor;
  d: path("M11.5 9.5h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12.5 13h-1a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 11.5 9.5");
}

.r-d8tkevd {
  d: path("M11.5 5h1a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 12.5 13h-1a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 11.5 5m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 13h-1A1.75 1.75 0 0 1 17 11.25v-4.5A1.75 1.75 0 0 1 18.75 5");
}

.z538azd9b {
  fill: currentColor;
  d: path("M4.25 5h1A1.75 1.75 0 0 1 7 6.75v4.5A1.75 1.75 0 0 1 5.25 13h-1a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 4.25 5");
}

</style>
