<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="awmc0ybgj"/><path class="ior2tub3d"/><path class="nex0q68jd"/><path class="ab69i60qd"/><path class="qebvfnl4i"/><path class="uxyzhxvwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-length-duotone-bold" /></template>
<style>
.ab69i60qd {
  d: path("M5.5 4H3v16h2.5");
}

.awmc0ybgj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ior2tub3d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 4H21v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nex0q68jd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qebvfnl4i {
  d: path("M18.5 4H21v16h-2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

</style>
