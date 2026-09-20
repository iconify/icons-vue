<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jld273cnz"/><path class="ngog6l_tc"/><path class="tkahp9b1r"/><path class="vokybza2s"/><path class="xbdh32u_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bandage-duotone-bold" /></template>
<style>
.jld273cnz {
  fill: currentColor;
  d: path("M3 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ngog6l_tc {
  fill: currentColor;
  d: path("M7 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.tkahp9b1r {
  d: path("M3 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.vokybza2s {
  d: path("M7 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xbdh32u_w {
  d: path("M17 12h4v7");
}

</style>
