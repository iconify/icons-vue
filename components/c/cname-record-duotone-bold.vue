<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="v79iaqbup"/><path class="xaz90clio"/><path class="y-r8d3bfy"/><path class="c_-m7_8tq"/><path class="k6nj2fbya"/><path class="ae-e09b3w"/><path class="rkhcgsbdl"/><path class="zbpm1d36f"/><path class="hrjweb57d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cname-record-duotone-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.c_-m7_8tq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hrjweb57d {
  d: path("m9 15 3 -3 3 3");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-r8d3bfy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zbpm1d36f {
  d: path("m9 8 3 -3 3 3");
}

</style>
