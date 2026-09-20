<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="emu6orblz"/><path class="f0mt8ybxt"/><path class="fbdov315v"/><path class="jdh6pf7zv"/><path class="tm05ptb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:living-room-outline-bold" /></template>
<style>
.emu6orblz {
  d: path("M2 17V9h8v8");
}

.f0mt8ybxt {
  d: path("M2 13h8");
}

.fbdov315v {
  d: path("m13 10 3 -3h3l3 3Z");
}

.jdh6pf7zv {
  d: path("M17.5 10v9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tm05ptb3a {
  d: path("M15.5 19h4");
}

</style>
