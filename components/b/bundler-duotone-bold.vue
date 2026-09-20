<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3f9rp43w"/><path class="fpd9j3buh"/><path class="h10-q0bxq"/><path class="orpw_8d9q"/><path class="gm3q67bcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bundler-duotone-bold" /></template>
<style>
.d3f9rp43w {
  fill: currentColor;
  d: path("M11 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fpd9j3buh {
  d: path("M2 8h9");
}

.gm3q67bcx {
  d: path("M11 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

.h10-q0bxq {
  d: path("M2 12h9");
}

.orpw_8d9q {
  d: path("M2 16h9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
