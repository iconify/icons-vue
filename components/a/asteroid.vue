<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a52i2oy6y"/><circle class="c_pvp7bsw"/><circle class="lv0lhdc4y"/><circle class="pnlbaejag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:asteroid" /></template>
<style>
.a52i2oy6y {
  d: path("m4.21 9.29l1.33-1.58Q7 6 9.24 6.19l1.52.12q2.24.19 3.83 1.78l1.32 1.32q1.59 1.59 1.25 3.81l-.32 2.06q-.34 2.22-2.25 3.41l-2.18 1.37q-1.91 1.19-3.96.25l-1.9-.87q-2.05-.94-2.56-3.13l-.73-3.12q-.51-2.19.95-3.9");
}

.c_pvp7bsw {
  cx: 8.5px;
  cy: 11.5px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lv0lhdc4y {
  cx: 11.75px;
  cy: 16.25px;
  r: 1.25px;
}

.pnlbaejag {
  cx: 18.75px;
  cy: 4.75px;
  r: 2px;
}

</style>
