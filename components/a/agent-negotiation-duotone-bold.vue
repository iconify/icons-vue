<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ydkocbbew"/><path class="xj1sznbnm"/><path class="gtu65_-tb"/><path class="uyhr05-fp"/><path class="t_29_5bvj"/><path class="gnioxz0xf"/><path class="h7k_twb0c"/><path class="x1wxn1ypz"/><path class="wm0jgrm5t"/><path class="wy-6ptr_q"/><path class="oi40jf9zq"/><path class="xb0ugqbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-negotiation-duotone-bold" /></template>
<style>
.gnioxz0xf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtu65_-tb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 9v2.5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.oi40jf9zq {
  d: path("M7.5 15v-2.5H10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_29_5bvj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 15v-2.5H10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uyhr05-fp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 16 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wm0jgrm5t {
  d: path("M16.5 9v2.5H14");
}

.wy-6ptr_q {
  d: path("m11 16 -3 -3");
}

.x1wxn1ypz {
  d: path("m13 8 3 3");
}

.xb0ugqbkt {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

.xj1sznbnm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 8 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ydkocbbew {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
