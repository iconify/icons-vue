<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qoibgxtiv"/><path class="vgxm_rbmc"/><path class="rtzyu2rle"/><path class="nn3mbubli"/><path class="uw5kuce7r"/><path class="j41x8568l"/><path class="zdse1fb0u"/><path class="cfq8fpb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-left-obj-duotone-bold" /></template>
<style>
.cfq8fpb9k {
  d: path("M5.5 17H12");
}

.j41x8568l {
  d: path("M5.5 7H15");
}

.nn3mbubli {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 17H12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qoibgxtiv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rtzyu2rle {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 12H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.vgxm_rbmc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 7H15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zdse1fb0u {
  d: path("M5.5 12H19");
}

</style>
