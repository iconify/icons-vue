<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="umk6tub1s"/><path class="bhlvvmwkr"/><path class="i4el9ihhm"/><path class="wt76_hbmn"/><path class="g9c4ykb9u"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-duotone-bold" /></template>
<style>
.bhlvvmwkr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.i4el9ihhm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.umk6tub1s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

</style>
