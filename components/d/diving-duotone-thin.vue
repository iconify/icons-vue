<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gl2wyfu4j"/><path class="pg8robb9a"/><path class="z449eibvb"/><path class="rw2clob2u"/><path class="b-zvzmq4t"/><path class="qj_kcbc2q"/><path class="q686vz2zk"/><path class="intk4nbhb"/><path class="g1wm5cc6f"/><path class="d147n4bfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diving-duotone-thin" /></template>
<style>
.b-zvzmq4t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.intk4nbhb {
  d: path("M16 10v5");
}

.pg8robb9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qj_kcbc2q {
  d: path("M3 6h10");
}

.rw2clob2u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 15 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z449eibvb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
