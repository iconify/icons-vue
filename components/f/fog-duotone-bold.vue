<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="u-xjqw_1i"/><path class="gam3cw54g"/><path class="zpzhbw1nh"/><path class="xgrfb-bqu"/><path class="vzfmp7bra"/><path class="ys-dg812g"/><path class="wneoubc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fog-duotone-bold" /></template>
<style>
.gam3cw54g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-xjqw_1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzfmp7bra {
  d: path("M5 11h14");
}

.wneoubc6n {
  d: path("M7 21h10");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.ys-dg812g {
  d: path("M3 16h18");
}

.zpzhbw1nh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
