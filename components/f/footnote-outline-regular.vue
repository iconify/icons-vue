<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="tu0fdo1xi"/><path class="qvytntb8g"/><path class="gfaw-ob9v"/><path class="fgdzphbre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:footnote-outline-regular" /></template>
<style>
.fgdzphbre {
  d: path("M7 18h8");
}

.gfaw-ob9v {
  d: path("M7 15h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvytntb8g {
  d: path("M7 10h10");
}

.tu0fdo1xi {
  d: path("M7 7h10");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
