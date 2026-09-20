<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czo2s0b0e"/><path class="i7n1d_bbc"/><path class="ucgcbdi9f"/><path class="wt76_hbmn"/><path class="g9c4ykb9u"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-duotone-thin" /></template>
<style>
.czo2s0b0e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7n1d_bbc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.ucgcbdi9f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

</style>
