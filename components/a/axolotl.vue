<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bitb-p09l"/><path class="pg4bj9beb"/><path class="rcetuec_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:axolotl" /></template>
<style>
.bitb-p09l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5c0-2.5 2-4 4.5-4C9 8.5 10 9.5 11 10c4-.25 7-1.5 10 .5c-3.25 2.5-6 3.75-9 3.75C10.5 15.5 9 16 7.25 16C4.75 16 3 14.5 3 12.5");
}

.pg4bj9beb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5c0-1.25.25-2.5 1-3.5m.94 4.06c.25-1.25.75-2.5 1.75-3.5M11 10c.5-1.25 1.5-2.25 2.75-2.75m-10 6.25c1 .75 2.25 1 3.5.75M10 15.4l-.5 2.35m6-3.75l.25 2.25");
}

.rcetuec_b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
