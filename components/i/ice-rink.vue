<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtnjfzbqn"/><path class="ebeg3zbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-rink" /></template>
<style>
.ebeg3zbmm {
  d: path("M9.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6.5 12h.01m10.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtnjfzbqn {
  d: path("M9.5 5h5a7 7 0 0 1 7 7a7 7 0 0 1-7 7h-5a7 7 0 0 1-7-7a7 7 0 0 1 7-7M12 5v14");
}

</style>
