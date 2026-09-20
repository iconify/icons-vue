<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="jb_v2ub8s"/><path class="lqj39lbjv"/><path class="gghaaub-j"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="vslz5yb3q"/><path class="cvahx_bgf"/><path class="ji1cfccfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-alive-duotone-bold" /></template>
<style>
.cvahx_bgf {
  d: path("m9 9 3 -3 3 3");
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gghaaub-j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jb_v2ub8s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ji1cfccfb {
  d: path("m9 15 3 3 3 -3");
}

.lqj39lbjv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 9 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ph8xawbhr {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
