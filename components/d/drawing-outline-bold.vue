<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yy6kkpb1q"/><path class="yv9cwobex"/><path class="uistg-qvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drawing-outline-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uistg-qvk {
  d: path("m13 16 -3 3h3");
}

.yv9cwobex {
  d: path("m12 15 7 -7 2 2 -7 7Z");
}

.yy6kkpb1q {
  d: path("M3 3v13h12V3Z");
}

</style>
