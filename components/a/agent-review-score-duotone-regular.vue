<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ookcwkbmf"/><path class="j29vm_ymj"/><path class="d041m248a"/><path class="a1ex7yb4g"/><path class="rfpc8ubdp"/><path class="b1ew5xbzw"/><path class="ls68ftbad"/><path class="jvpr04bkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-review-score-duotone-regular" /></template>
<style>
.a1ex7yb4g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b1ew5xbzw {
  d: path("M14 13v5");
}

.d041m248a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j29vm_ymj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvpr04bkw {
  d: path("M21 15v3");
}

.ls68ftbad {
  d: path("M17.5 9v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ookcwkbmf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfpc8ubdp {
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
}

</style>
