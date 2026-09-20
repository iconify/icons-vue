<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lppzsmemb"/><path class="utlpmrn-a"/><path class="m557ps9ux"/><path class="flscefshg"/><path class="irf6xy5kk"/><path class="x50q_4bdr"/><path class="i7iskytip"/><path class="ege_q3bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gift-open-duotone-bold" /></template>
<style>
.ege_q3bkn {
  d: path("m8 5 2 -2");
}

.flscefshg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i7iskytip {
  d: path("m13 6 3 -3");
}

.irf6xy5kk {
  d: path("M5 13v8h14v-8");
}

.lppzsmemb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13v8h14v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m557ps9ux {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.utlpmrn-a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
