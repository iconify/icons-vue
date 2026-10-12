<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h_q2whbfc"/><path class="ernrutldi"/><path class="itw1zrbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compost-heap" /></template>
<style>
.ernrutldi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 17.5h.01M13 15.25h.01m2.74 3h.01");
}

.h_q2whbfc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25c0-5 4-8.5 9.25-8.5s9.25 3.5 9.25 8.5a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1");
}

.itw1zrbnj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.75c-1-1.25 1-2.25 0-3.5M12 7.5c-1-1.25 1-2.25 0-3.5m3.5 4.75c-1-1.25 1-2.25 0-3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
