<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tbridd90x"/><path class="yf982jbnt"/><path class="j587xtbwm"/><path class="asaq2m23g"/><path class="uih_zvhtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:autumn-duotone-bold" /></template>
<style>
.asaq2m23g {
  d: path("m15 20 4 -4");
}

.j587xtbwm {
  d: path("m14 15 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tbridd90x {
  fill: currentColor;
  d: path("M6 14C6 8 10 4 16 4c0 6 -4 10 -10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uih_zvhtv {
  d: path("M4 21h16");
}

.yf982jbnt {
  d: path("M6 14C6 8 10 4 16 4c0 6 -4 10 -10 10");
}

</style>
