<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-g-_s4ku"/><path class="ki-5h0s5c"/><path class="betk_pbkd"/><path class="uwq4cli8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunk-size-outline-thin" /></template>
<style>
.betk_pbkd {
  d: path("M8 4 6 6l2 2");
}

.f-g-_s4ku {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki-5h0s5c {
  d: path("M6 6h12");
}

.uwq4cli8g {
  d: path("m16 4 2 2 -2 2");
}

</style>
