<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ot2i-pb1g"/><path class="h-6x62mls"/><path class="l0ecuoq5i"/><path class="ze9yihd5h"/><path class="k-jt90-vx"/><path class="b-73d8bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carousel-outline-thin" /></template>
<style>
.b-73d8bgy {
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.l0ecuoq5i {
  d: path("m20 7 2 2 -2 2");
}

.ot2i-pb1g {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.ze9yihd5h {
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
