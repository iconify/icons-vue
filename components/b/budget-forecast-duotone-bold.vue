<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mliavyjyi"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="uubzstacn"/><path class="ywjxqgbvl"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x9ne0caxf"/><path class="ks612kq_w"/><path class="boj5jfb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-forecast-duotone-bold" /></template>
<style>
.boj5jfb_k {
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ks612kq_w {
  d: path("m7 17 5 -5");
}

.mliavyjyi {
  fill: currentColor;
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uubzstacn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x9ne0caxf {
  d: path("M7 8h12");
}

.ywjxqgbvl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
