<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0x1wbxg"/><path class="ja7s-m1mr"/><path class="x_r014yat"/><path class="yj0miubwd"/><path class="mcubrkb2y"/><path class="x1_r36phd"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:current-account-duotone-thin" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja7s-m1mr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.x_r014yat {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x1_r36phd {
  d: path("M9 12h6");
}

.x3sflacnk {
  d: path("M9 18h6");
}

.yj0miubwd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yw0x1wbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
