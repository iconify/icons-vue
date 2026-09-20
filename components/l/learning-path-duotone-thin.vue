<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhcvwjnws"/><path class="yqql_ccjj"/><path class="advi1_bna"/><path class="a-ud5-dfd"/><path class="gghvfjb1o"/><path class="h5sglqb0f"/><path class="h3z56pbbf"/><path class="z_si_bbvo"/><path class="a51oytv8p"/><path class="pv_diebju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:learning-path-duotone-thin" /></template>
<style>
.a-ud5-dfd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 20 5 -5v-5l5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.a51oytv8p {
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.advi1_bna {
  fill: currentColor;
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gghvfjb1o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 21h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h3z56pbbf {
  d: path("M2 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h5sglqb0f {
  d: path("m4 20 5 -5v-5l5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv_diebju {
  d: path("M17 21h4");
}

.yqql_ccjj {
  fill: currentColor;
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z_si_bbvo {
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zhcvwjnws {
  fill: currentColor;
  d: path("M2 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
