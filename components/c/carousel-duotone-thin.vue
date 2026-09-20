<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lctvlf08r"/><path class="e17y6ccrm"/><path class="wm7ubgban"/><path class="kn8jv2buv"/><path class="ot2i-pb1g"/><path class="h-6x62mls"/><path class="l0ecuoq5i"/><path class="ze9yihd5h"/><path class="k-jt90-vx"/><path class="b-73d8bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carousel-duotone-thin" /></template>
<style>
.b-73d8bgy {
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e17y6ccrm {
  fill: currentColor;
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h-6x62mls {
  d: path("M4 7 2 9l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-jt90-vx {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kn8jv2buv {
  fill: currentColor;
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l0ecuoq5i {
  d: path("m20 7 2 2 -2 2");
}

.lctvlf08r {
  fill: currentColor;
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ot2i-pb1g {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.wm7ubgban {
  fill: currentColor;
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ze9yihd5h {
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
