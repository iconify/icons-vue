<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezg__mbcy"/><path class="d44kz-bgz"/><path class="ohwixhb-v"/><path class="pfiht2bcx"/><path class="fm4oowb-p"/><path class="tp8vjxbvr"/><path class="m_812vyum"/><path class="qml-hybqn"/><path class="u4sowhi7h"/><path class="if5ft31dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-notify-duotone-regular" /></template>
<style>
.d44kz-bgz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ezg__mbcy {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fm4oowb-p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.if5ft31dv {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.m_812vyum {
  d: path("M6 12v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohwixhb-v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pfiht2bcx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qml-hybqn {
  d: path("M18 12v4");
}

.tp8vjxbvr {
  d: path("M6 12a6 6 0 0 1 12 0");
}

.u4sowhi7h {
  d: path("M4 16h16");
}

</style>
