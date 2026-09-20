<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c7u-w2bad"/><path class="xbdnj9ayw"/><path class="xienbiity"/><path class="ph-bhccoq"/><path class="tobs8svpc"/><path class="oe1ogfbua"/><path class="k4lkwhjuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cost-per-call-duotone-bold" /></template>
<style>
.c7u-w2bad {
  fill: currentColor;
  d: path("M7 7a5 5 0 1 0 10 0A5 5 0 1 0 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k4lkwhjuc {
  d: path("M4 20h9");
}

.oe1ogfbua {
  d: path("m15.5 14 2 2 -2 2");
}

.ph-bhccoq {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tobs8svpc {
  d: path("M4 16h13");
}

.xbdnj9ayw {
  fill: currentColor;
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xienbiity {
  d: path("M7 7a5 5 0 1 0 10 0A5 5 0 1 0 7 7");
}

</style>
