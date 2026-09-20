<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmlhv041j"/><path class="b9d1wzyqr"/><path class="fv84_bbid"/><path class="ja7s-m1mr"/><path class="fnf6pdbdu"/><path class="xwissob6k"/><path class="d4f9j2bku"/><path class="x1_r36phd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drawing-compass-duotone-thin" /></template>
<style>
.b9d1wzyqr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9 -6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d4f9j2bku {
  d: path("m12 9 6 6v4");
}

.fnf6pdbdu {
  d: path("M12 3v6");
}

.fv84_bbid {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9 6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja7s-m1mr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jmlhv041j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x1_r36phd {
  d: path("M9 12h6");
}

.xwissob6k {
  d: path("m12 9 -6 6v4");
}

</style>
