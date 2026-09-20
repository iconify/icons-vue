<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p6an06b6t"/><path class="h03wmtogt"/><path class="hy6l_ib5n"/><path class="vc21npdlz"/><path class="o9xw2hwjb"/><path class="tt7ypiikb"/><path class="zgod0v2rr"/><path class="du3agkbjb"/><path class="objyy5b5b"/><path class="r2dk7difb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-branch-add-duotone-bold" /></template>
<style>
.du3agkbjb {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h03wmtogt {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hy6l_ib5n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o9xw2hwjb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.objyy5b5b {
  d: path("M17 9v6");
}

.p6an06b6t {
  fill: currentColor;
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r2dk7difb {
  d: path("M14 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tt7ypiikb {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vc21npdlz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgod0v2rr {
  d: path("M7 8.5v7");
}

</style>
