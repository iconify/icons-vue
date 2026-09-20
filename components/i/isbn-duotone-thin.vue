<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8v713bgf"/><path class="y7f50bciz"/><path class="xxaapacaw"/><path class="hl01jfb_m"/><path class="wps-pe_mv"/><path class="yu-j7jb_g"/><path class="qltxbpdvm"/><path class="tr_jskylo"/><path class="z3it7clmt"/><path class="leemd3bqp"/><path class="h9fb_9biv"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:isbn-duotone-thin" /></template>
<style>
.h9fb_9biv {
  d: path("M20 5v12");
}

.hl01jfb_m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leemd3bqp {
  d: path("M15 5v12");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qltxbpdvm {
  d: path("M4 5v12");
}

.tr_jskylo {
  d: path("M7 5v12");
}

.w8v713bgf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wps-pe_mv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xxaapacaw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y7f50bciz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z3it7clmt {
  d: path("M11 5v12");
}

</style>
