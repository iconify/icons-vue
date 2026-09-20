<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e-7eylbmz"/><path class="j7q0iebzu"/><path class="ugjxj4v5w"/><path class="re8yolbvl"/><path class="ws-a642hy"/><path class="jalxicbwq"/><path class="i2y9aacrj"/><path class="jllte9bnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:estate-duotone-bold" /></template>
<style>
.e-7eylbmz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i2y9aacrj {
  d: path("m12 12 5 -5 5 5");
}

.j7q0iebzu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jalxicbwq {
  d: path("M3.5 12v8h7v-8");
}

.jllte9bnc {
  d: path("M13.5 12v8h7v-8");
}

.re8yolbvl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ugjxj4v5w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ws-a642hy {
  d: path("m2 12 5 -5 5 5");
}

</style>
