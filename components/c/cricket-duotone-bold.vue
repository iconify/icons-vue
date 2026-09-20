<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4e9xwitt"/><path class="lehy25blz"/><path class="fg_a8lwva"/><path class="zt2ojnbyc"/><path class="epoh96bbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cricket-duotone-bold" /></template>
<style>
.epoh96bbt {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fg_a8lwva {
  d: path("M6 3h6v11H6Z");
}

.k4e9xwitt {
  fill: currentColor;
  d: path("M6 3h6v11H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lehy25blz {
  fill: currentColor;
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.zt2ojnbyc {
  d: path("M9 14v7");
}

</style>
