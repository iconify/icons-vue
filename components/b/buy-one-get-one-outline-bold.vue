<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vo1-lv2pt"/><path class="oz3eccbug"/><path class="rza2khwwm"/><path class="v1-or777z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buy-one-get-one-outline-bold" /></template>
<style>
.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.rza2khwwm {
  d: path("M7 13h3.5v4H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v1-or777z {
  d: path("M13.5 13H17v4h-3.5Z");
}

.vo1-lv2pt {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
