<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z640i9ymj"/><path class="sgjb9gifn"/><path class="zka_zabrc"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:contract-test-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sgjb9gifn {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
}

.z640i9ymj {
  fill: currentColor;
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zka_zabrc {
  d: path("M9 13h6");
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
