<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jy2rzibrh"/><path class="fgqk6gbgn"/><path class="xpov22bfs"/><path class="acnb1hz5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:absent-outline-regular" /></template>
<style>
.acnb1hz5q {
  d: path("m22 14 -6 6");
}

.fgqk6gbgn {
  d: path("M2.4 16a6.6 6.6 0 0 1 13.2 0");
}

.jy2rzibrh {
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xpov22bfs {
  d: path("m16 14 6 6");
}

</style>
