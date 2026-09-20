<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yd6s8k6vu"/><path class="rdtau096c"/><path class="ebvczzbhc"/><path class="tpzwlmbef"/><path class="ivstp2b7y"/><path class="b3s4djbny"/><path class="mw6526b2i"/><path class="sxlwlmkmh"/><path class="eskbyryvt"/><path class="hc7fbd-jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grad-flow-duotone-bold" /></template>
<style>
.b3s4djbny {
  d: path("M4 5h16");
}

.ebvczzbhc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eskbyryvt {
  d: path("m10 14.5 2 2 2 -2");
}

.hc7fbd-jo {
  d: path("M4 19h16");
}

.ivstp2b7y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mw6526b2i {
  d: path("m10 7.5 2 2 2 -2");
}

.rdtau096c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7.5 2 2 2 -2");
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

.tpzwlmbef {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 14.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yd6s8k6vu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
