<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yqib8cbsw"/><path class="huksvxwzw"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delivery-truck-sharp" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.huksvxwzw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 7.5v2.75H18m-12.5-2H11v4.5H5.5z");
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

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yqib8cbsw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7V5.5h12.1l1.115.001l.585.949l2.2 3.55l1.9.95l.554.279l-.004.621v4.9H2.75v-1.5Z");
}

</style>
