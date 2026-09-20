<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yf982jbnt"/><path class="j587xtbwm"/><path class="asaq2m23g"/><path class="uih_zvhtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:autumn-outline-thin" /></template>
<style>
.asaq2m23g {
  d: path("m15 20 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j587xtbwm {
  d: path("m14 15 4 4");
}

.uih_zvhtv {
  d: path("M4 21h16");
}

.yf982jbnt {
  d: path("M6 14C6 8 10 4 16 4c0 6 -4 10 -10 10");
}

</style>
