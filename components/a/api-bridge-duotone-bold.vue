<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="layh4jhoz"/><path class="pu3hkerir"/><path class="ebvczzbhc"/><path class="mn53ufu2b"/><path class="md3qg6xkk"/><path class="bvirm9d4j"/><path class="sxlwlmkmh"/><path class="n90p24bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-bridge-duotone-bold" /></template>
<style>
.bvirm9d4j {
  d: path("M20 6v12");
}

.ebvczzbhc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.layh4jhoz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.mn53ufu2b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n90p24bmq {
  d: path("m10 10 2 2 -2 2");
}

.pu3hkerir {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

</style>
