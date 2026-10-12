<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xga4-ubjl"/><path class="axlbu-bbs"/><path class="gzrsdzb0g"/><path class="hg-wfqbbx"/><path class="rlama4bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garlic-press-sharp" /></template>
<style>
.axlbu-bbs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 7.5h.01");
}

.gzrsdzb0g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.25h9v6H6z");
}

.hg-wfqbbx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12.25h.01m2.99 0h.01");
}

.rlama4bbp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 17.75v2.75m2.5-2.75v2.75m2.5-2.75v2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xga4-ubjl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.25 7.5l17.5-4.25M3.25 7.5L5 9.25h15.75");
}

</style>
