<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="okud9xj_d"/><path class="brjpv3b7t"/><path class="raivi4yli"/><path class="i50mf1njm"/><path class="ct75s-bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:connecting-flight-outline-bold" /></template>
<style>
.brjpv3b7t {
  d: path("M17.5 6.5V11");
}

.ct75s-bnk {
  d: path("m12 9 3 3 -3 3");
}

.i50mf1njm {
  d: path("m7 9 3 3 -3 3");
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.raivi4yli {
  d: path("M17.5 13v4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
