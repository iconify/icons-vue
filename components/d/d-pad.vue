<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zj5l73zwp"/><path class="hqn_f6b_h"/><circle class="zhtdkvboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:d-pad" /></template>
<style>
.hqn_f6b_h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01M18.25 12h.01M12 18.25h.01M5.75 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhtdkvboy {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zj5l73zwp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4q1.25 0 1.25 1.25v3.5q0 1.25 1.25 1.25H20q1.25 0 1.25 1.25v4q0 1.25-1.25 1.25h-3.5q-1.25 0-1.25 1.25V20q0 1.25-1.25 1.25h-4q-1.25 0-1.25-1.25v-3.5q0-1.25-1.25-1.25H4q-1.25 0-1.25-1.25v-4q0-1.25 1.25-1.25h3.5q1.25 0 1.25-1.25V4q0-1.25 1.25-1.25");
}

</style>
