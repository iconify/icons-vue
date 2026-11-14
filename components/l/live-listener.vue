<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fk3pdublz"/><path class="y2mekvg7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-listener" /></template>
<style>
.fk3pdublz {
  d: path("M5 10.5v-1a7 7 0 0 1 14 0v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2mekvg7y {
  d: path("M5 9.5zA1.5 1.5 0 0 1 6.5 11v2A1.5 1.5 0 0 1 5 14.5A1.5 1.5 0 0 1 3.5 13v-2A1.5 1.5 0 0 1 5 9.5m14 0za1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-2A1.5 1.5 0 0 1 19 9.5m-10 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-4 12c0-3 3-5 7-5s7 2 7 5");
}

</style>
