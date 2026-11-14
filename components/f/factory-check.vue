<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rv-gx1byr"/><path class="suakxsbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:factory-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rv-gx1byr {
  d: path("M12.1 19H2.5V9l6-4.5V9l6-4.5V9l6-4.5V13");
}

.suakxsbaz {
  d: path("M7.5 13H8a1.5 1.5 0 0 1 1.5 1.5v3A1.5 1.5 0 0 1 8 19h-.5A1.5 1.5 0 0 1 6 17.5v-3A1.5 1.5 0 0 1 7.5 13m7.25 5l2 2L21 15.75");
}

</style>
