<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gl2wyfu4j"/><path class="qgk4iv8ds"/><path class="aeyrv6w7v"/><path class="mbbkdlooc"/><path class="bkybkjb9o"/><path class="qj_kcbc2q"/><path class="q686vz2zk"/><path class="intk4nbhb"/><path class="g1wm5cc6f"/><path class="d147n4bfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diving-duotone-bold" /></template>
<style>
.aeyrv6w7v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bkybkjb9o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d147n4bfy {
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
}

.g1wm5cc6f {
  d: path("m16 15 -3 3");
}

.gl2wyfu4j {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.intk4nbhb {
  d: path("M16 10v5");
}

.mbbkdlooc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 15 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qgk4iv8ds {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qj_kcbc2q {
  d: path("M3 6h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
