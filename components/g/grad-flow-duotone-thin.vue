<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1n3csb_d"/><path class="v8j8xd4zc"/><path class="j2r1pso3k"/><path class="isyb2ybpg"/><path class="a0z12hbex"/><path class="b3s4djbny"/><path class="mw6526b2i"/><path class="sxlwlmkmh"/><path class="eskbyryvt"/><path class="hc7fbd-jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grad-flow-duotone-thin" /></template>
<style>
.a0z12hbex {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.a1n3csb_d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b3s4djbny {
  d: path("M4 5h16");
}

.eskbyryvt {
  d: path("m10 14.5 2 2 2 -2");
}

.hc7fbd-jo {
  d: path("M4 19h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isyb2ybpg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 14.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2r1pso3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mw6526b2i {
  d: path("m10 7.5 2 2 2 -2");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.v8j8xd4zc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 7.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
