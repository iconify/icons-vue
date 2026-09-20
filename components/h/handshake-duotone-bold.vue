<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="hk9el0b4x"/><path class="gh_yv3cdy"/><path class="ht8944b0y"/><path class="wi90dig0u"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="f8gsx7b5s"/><path class="qs69rnufu"/><path class="xqfhg19ie"/><path class="q9rcsymqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handshake-duotone-bold" /></template>
<style>
.f8gsx7b5s {
  d: path("M6 8h12");
}

.fcstqn4mf {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gh_yv3cdy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 8 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hk9el0b4x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ht8944b0y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ph8xawbhr {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q9rcsymqn {
  d: path("m6 16 3 3");
}

.qs69rnufu {
  d: path("m18 8 -3 -3");
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

.wi90dig0u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xqfhg19ie {
  d: path("M18 16H6");
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
