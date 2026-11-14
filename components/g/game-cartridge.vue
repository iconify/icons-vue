<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mwjyxhb-l"/><path class="y1mvy4opn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:game-cartridge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwjyxhb-l {
  d: path("M4 4.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V15l-1.5 1.5v5h-13v-5L4 15Z");
}

.y1mvy4opn {
  d: path("M8.75 5.5h6.5A1.75 1.75 0 0 1 17 7.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 10.75v-3.5A1.75 1.75 0 0 1 8.75 5.5M8.5 19h7");
}

</style>
