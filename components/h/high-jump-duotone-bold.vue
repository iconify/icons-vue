<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w-5salb9v"/><path class="ryj_7f_2r"/><path class="gl1_5db2m"/><path class="pgaf_h5qy"/><path class="m1mjigbsi"/><path class="ml3aqbbkk"/><path class="t1tm72bkp"/><path class="zyvg9rbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:high-jump-duotone-bold" /></template>
<style>
.gl1_5db2m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m1mjigbsi {
  d: path("M4 8h16");
}

.ml3aqbbkk {
  d: path("M4 8v12");
}

.pgaf_h5qy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15c2 -7 10 -7 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ryj_7f_2r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1tm72bkp {
  d: path("M20 8v12");
}

.w-5salb9v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zyvg9rbxb {
  d: path("M6 15c2 -7 10 -7 12 0");
}

</style>
