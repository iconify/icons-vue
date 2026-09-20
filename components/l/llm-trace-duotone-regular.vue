<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="g60t3db9d"/><path class="bxffck7nz"/><path class="m_fy-w1gx"/><path class="crv4i00bu"/><path class="nfb4ipisv"/><path class="b603-acaz"/><path class="pqv-otbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:llm-trace-duotone-regular" /></template>
<style>
.b603-acaz {
  d: path("M10 12h8");
}

.bxffck7nz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.g60t3db9d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_fy-w1gx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nfb4ipisv {
  d: path("M7 7h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqv-otbrp {
  d: path("M13 17h8");
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
