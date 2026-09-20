<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-yh3actq"/><path class="rw6ho_bav"/><path class="asewlgb2k"/><path class="mvm7r4bea"/><path class="mtc590bck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:date-range-outline-thin" /></template>
<style>
.asewlgb2k {
  d: path("M6 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtc590bck {
  d: path("M16 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.v-yh3actq {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
