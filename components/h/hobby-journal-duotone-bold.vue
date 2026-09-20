<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ucf3ueb9q"/><path class="diipsobkl"/><path class="wuvisubmw"/><path class="zsd3khm8o"/><path class="ws9v8zbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hobby-journal-duotone-bold" /></template>
<style>
.diipsobkl {
  d: path("M5 3v18h14V3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ucf3ueb9q {
  fill: currentColor;
  d: path("M5 3v18h14V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ws9v8zbhe {
  d: path("M11 16h6");
}

.wuvisubmw {
  d: path("M8 3v18");
}

.zsd3khm8o {
  d: path("M16 3v9l-2 -2 -2 2V3");
}

</style>
