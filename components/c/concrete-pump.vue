<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yk9sh642y"/><path class="zp4py3bns"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:concrete-pump" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0haxibzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yk9sh642y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-1.75q0-1.25.67-2.3l.41-.65q.67-1.05 1.92-1.05h1.5Q8.5 9.75 8.5 11v1q0 1.25 1.25 1.25H20q1.25 0 1.25 1.25v1q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25");
}

.zp4py3bns {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 13.25v-3H18l-2-6.5h4.5m0 0c.5 1.5.5 3-.25 4.5");
}

</style>
