<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpm6v1-ys"/><path class="t87z9eb3a"/><path class="mkx4nibwc"/><path class="ezdu6ccav"/><path class="jkuojibnm"/><path class="nn2mbucfp"/><path class="wwyi7ubez"/><path class="om9c7ck0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-vs-actual-duotone-bold" /></template>
<style>
.ezdu6ccav {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mkx4nibwc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 20v-6h5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nn2mbucfp {
  d: path("M5 20V8h5v12");
}

.om9c7ck0x {
  d: path("M13 8h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t87z9eb3a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 20V8h5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwyi7ubez {
  d: path("M14 20v-6h5v6");
}

</style>
