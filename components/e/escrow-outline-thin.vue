<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o610cu0jy"/><path class="u_pwg_bmr"/><path class="zzarb32zm"/><path class="qbdmmsbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escrow-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o610cu0jy {
  d: path("M2.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.qbdmmsbuw {
  d: path("M16 9a2 2 0 0 1 4 0");
}

.u_pwg_bmr {
  d: path("M7 10.5v3");
}

.zzarb32zm {
  d: path("M14 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3.5a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
