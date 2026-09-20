<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="xs_r_dj_f"/><path class="lx07rtb6m"/><path class="t_vzy4bhq"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="y09n-7bbz"/><path class="xjxf-fbjv"/><path class="z0_yphh3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-duotone-thin" /></template>
<style>
.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lx07rtb6m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.t_vzy4bhq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xjxf-fbjv {
  d: path("m13 9 2 -2");
}

.xs_r_dj_f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y09n-7bbz {
  d: path("m6 16 5 -5");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z0_yphh3l {
  d: path("m17 5 2 -2");
}

</style>
