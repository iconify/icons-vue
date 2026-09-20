<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="sz28udz1i"/><path class="bqh-ggfjw"/><path class="hpm6v1-ys"/><path class="k6nj2fbya"/><path class="rhp6fjekz"/><path class="a-768stfr"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:format-code-duotone-bold" /></template>
<style>
.a-768stfr {
  d: path("M8 15h13");
}

.bqh-ggfjw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
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

.k6nj2fbya {
  d: path("M3 5h18");
}

.rhp6fjekz {
  d: path("M8 10h13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sz28udz1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
