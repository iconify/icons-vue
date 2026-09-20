<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="sy21-w-qb"/><path class="f4s6nbboh"/><path class="sh7p6ed3z"/><path class="ftzd1cc_g"/><path class="skbifdbcx"/><path class="f2m4wubik"/><path class="zl61012kd"/><path class="u4kp6lp9x"/><path class="qyl16slsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-sync-duotone-bold" /></template>
<style>
.f2m4wubik {
  d: path("M13 12h8");
}

.f4s6nbboh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 9.5 21 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftzd1cc_g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 16.5 15 19l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qyl16slsb {
  d: path("M17.5 16.5 15 19l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sh7p6ed3z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 19h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.sy21-w-qb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u4kp6lp9x {
  d: path("M15 19h6");
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

</style>
