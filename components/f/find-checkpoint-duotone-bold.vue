<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ieioa6bqm"/><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="j3asw2s8u"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="hob4evbuj"/><path class="hrabrxb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:find-checkpoint-duotone-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.hob4evbuj {
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hrabrxb6m {
  d: path("M11.5 9.5 15 13");
}

.ieioa6bqm {
  fill: currentColor;
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j3asw2s8u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 9.5 15 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zwjzc3g_l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
