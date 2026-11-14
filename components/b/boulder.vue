<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggvxkebvq"/><path class="f23hlqbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boulder" /></template>
<style>
.f23hlqbso {
  d: path("M15.5 5L13 12l8.5 7m-15 0L8 15.5L7 13");
}

.ggvxkebvq {
  d: path("m2.966 17.136l1.443-5.774a1.5 1.5 0 0 1 .341-.639l3.892-4.325a1.5 1.5 0 0 1 .887-.479l5.274-.812a1.5 1.5 0 0 1 1.224.362l3.567 3.17a1.5 1.5 0 0 1 .487.899l1.161 7.739A1.5 1.5 0 0 1 19.758 19H4.421a1.5 1.5 0 0 1-1.455-1.864");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
