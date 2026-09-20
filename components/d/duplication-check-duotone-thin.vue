<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="mq3gpvbkh"/><path class="gihj4qbne"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jn24arf4i"/><path class="w8g3vrtdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:duplication-check-duotone-thin" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gihj4qbne {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jn24arf4i {
  d: path("M8 10h6");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.mq3gpvbkh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8g3vrtdm {
  d: path("M10 14h6");
}

</style>
