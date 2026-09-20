<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="umk6tub1s"/><path class="ydsys7qfb"/><path class="vflqlvuxi"/><path class="sygda3zfc"/><path class="or5ahrb2g"/><path class="wt76_hbmn"/><path class="l9cf9bbmd"/><path class="plqv1xi7k"/><path class="j_z-vb9qy"/><path class="xvmft_b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-all-duotone-bold" /></template>
<style>
.j_z-vb9qy {
  d: path("M10 15h10");
}

.l9cf9bbmd {
  d: path("M10 9h10");
}

.or5ahrb2g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 12.5 20 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plqv1xi7k {
  d: path("M17.5 6.5 20 9l-2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sygda3zfc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.umk6tub1s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vflqlvuxi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 6.5 20 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

.xvmft_b5k {
  d: path("M17.5 12.5 20 15l-2.5 2.5");
}

.ydsys7qfb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
