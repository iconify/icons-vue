<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i-cu8wbhl"/><path class="t6bqz9mcc"/><path class="aszec0xzq"/><path class="o22a_hbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bread-duotone-bold" /></template>
<style>
.aszec0xzq {
  d: path("m9 11 2 -2");
}

.i-cu8wbhl {
  fill: currentColor;
  d: path("M4 20v-7c0 -4 3 -6 8 -6s8 2 8 6v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o22a_hbrn {
  d: path("m13 11 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t6bqz9mcc {
  d: path("M4 20v-7c0 -4 3 -6 8 -6s8 2 8 6v7Z");
}

</style>
