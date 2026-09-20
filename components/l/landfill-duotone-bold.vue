<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gjrqt49vu"/><path class="xa9vorq4l"/><path class="agve3ib4g"/><path class="gpip01bqy"/><path class="bod4n0b3z"/><path class="e-n_8dpfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landfill-duotone-bold" /></template>
<style>
.agve3ib4g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 13 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.e-n_8dpfy {
  d: path("m9 13 2 -2");
}

.gjrqt49vu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gpip01bqy {
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xa9vorq4l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
