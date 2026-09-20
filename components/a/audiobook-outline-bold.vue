<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fse74oemj"/><path class="ocopvj5ps"/><path class="ic00xab8f"/><path class="cb9u5zbqi"/><path class="xyckaabnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audiobook-outline-bold" /></template>
<style>
.cb9u5zbqi {
  d: path("M2 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fse74oemj {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.ic00xab8f {
  d: path("M4 12a8 8 0 0 1 16 0");
}

.ocopvj5ps {
  d: path("M9 8v13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyckaabnm {
  d: path("M18 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
