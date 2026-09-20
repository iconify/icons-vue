<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okud9xj_d"/><path class="brjpv3b7t"/><path class="raivi4yli"/><path class="dpvrwwhil"/><path class="p87wbut5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:boarding-pass-outline-thin" /></template>
<style>
.brjpv3b7t {
  d: path("M17.5 6.5V11");
}

.dpvrwwhil {
  d: path("M5 9h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.p87wbut5y {
  d: path("M5 13h5");
}

.raivi4yli {
  d: path("M17.5 13v4.5");
}

</style>
