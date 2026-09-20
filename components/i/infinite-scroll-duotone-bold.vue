<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="utlpmrn-a"/><path class="ywrmwdg9d"/><path class="myjkkk6uj"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="ephqv81ta"/><path class="zrtfv65fm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:infinite-scroll-duotone-bold" /></template>
<style>
.ephqv81ta {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.myjkkk6uj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 18.5 12 21l2.5 -2.5");
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

.ywrmwdg9d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrtfv65fm {
  d: path("M9.5 18.5 12 21l2.5 -2.5");
}

</style>
