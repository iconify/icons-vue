<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c46evdbrq"/><path class="wujyfob1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-game-croquet" /></template>
<style>
.c46evdbrq {
  d: path("M4.25 14.5h.5a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-2.5a1.75 1.75 0 0 1 1.75-1.75m.25 0L7 3m2.25 17.5V12a4.75 4.75 0 0 1 9.5 0v8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wujyfob1j {
  d: path("M12 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
