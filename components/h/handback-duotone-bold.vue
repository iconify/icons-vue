<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nahkiebcp"/><path class="wh0sirbzw"/><path class="szwb3cbkd"/><path class="ltqx5y4us"/><path class="sxej68mlt"/><path class="zq_pavbka"/><path class="imjw6lo4s"/><path class="f-l8xfbfx"/><path class="yr5tx9l0o"/><path class="gsf5khfvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handback-duotone-bold" /></template>
<style>
.f-l8xfbfx {
  d: path("M10.5 11H13v2.5");
}

.gsf5khfvc {
  d: path("M16 10a3 3 0 0 1 6 0");
}

.imjw6lo4s {
  d: path("M8.5 15.5 11 13");
}

.ltqx5y4us {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 11H13v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nahkiebcp {
  fill: currentColor;
  d: path("M17 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.sxej68mlt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 10a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.szwb3cbkd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 15.5 11 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wh0sirbzw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yr5tx9l0o {
  d: path("M17 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zq_pavbka {
  d: path("M7.27 15.28a3 3 0 1 1 -2.54 0");
}

</style>
