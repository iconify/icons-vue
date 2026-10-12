<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="t2gi8bw3v"/><circle class="k7o8eob8y"/><path class="g5fuvacpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clown" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.g5fuvacpp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.25c1.25 2 3 3 5 3s3.75-1 5-3");
}

.k7o8eob8y {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2gi8bw3v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.5h.01m6.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
