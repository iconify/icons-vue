<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="myekf3bzc"/><path class="ef626bcbl"/><path class="rrxso7m3p"/><path class="i49-5fazd"/><path class="odx_lab8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:co-op-outline-bold" /></template>
<style>
.ef626bcbl {
  d: path("M3 17a4 4 0 0 1 8 0");
}

.i49-5fazd {
  d: path("M13 17a4 4 0 0 1 8 0");
}

.myekf3bzc {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.odx_lab8a {
  d: path("M10 6h4");
}

.rrxso7m3p {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
