<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmyobjb9w"/><path class="v-w8_9m4o"/><path class="wtr271uqu"/><path class="hf_gtezns"/><path class="nyba_zpqc"/><path class="nutam6ble"/><path class="n-7t0yb1r"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cite-sources-duotone-thin" /></template>
<style>
.gmyobjb9w {
  fill: currentColor;
  d: path("M17 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.nutam6ble {
  d: path("M17 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nyba_zpqc {
  d: path("M3 8h11");
}

.v-w8_9m4o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtr271uqu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
