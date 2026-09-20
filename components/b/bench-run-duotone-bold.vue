<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r14em7b4l"/><path class="ur9jjfbgq"/><path class="zx1hmsoqu"/><path class="i5be34b7d"/><path class="fav0kibck"/><path class="eex8q3rzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bench-run-duotone-bold" /></template>
<style>
.eex8q3rzp {
  d: path("M17 12h2.5");
}

.fav0kibck {
  d: path("M17 9.5V12");
}

.i5be34b7d {
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.r14em7b4l {
  fill: currentColor;
  d: path("m4 6 7 7 -7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ur9jjfbgq {
  fill: currentColor;
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zx1hmsoqu {
  d: path("m4 6 7 7 -7 7Z");
}

</style>
