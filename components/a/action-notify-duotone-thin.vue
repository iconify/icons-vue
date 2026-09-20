<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezg__mbcy"/><path class="uxwbq-n4s"/><path class="shq6z05au"/><path class="vvumupblr"/><path class="gnqb99ipa"/><path class="tp8vjxbvr"/><path class="m_812vyum"/><path class="qml-hybqn"/><path class="u4sowhi7h"/><path class="if5ft31dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-notify-duotone-thin" /></template>
<style>
.ezg__mbcy {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gnqb99ipa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.if5ft31dv {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.m_812vyum {
  d: path("M6 12v4");
}

.qml-hybqn {
  d: path("M18 12v4");
}

.shq6z05au {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tp8vjxbvr {
  d: path("M6 12a6 6 0 0 1 12 0");
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.uxwbq-n4s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvumupblr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
