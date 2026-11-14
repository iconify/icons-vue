<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3w4iztoh"/><path class="ibh_yx7my"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fleet-map" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibh_yx7my {
  d: path("M11 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.j3w4iztoh {
  d: path("M16 8.75V3l-4.75 1.5L6.75 3L2.5 4.5V15l4.25-1.5V3m4.5 1.5v4.25m0 2.75h3.5a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M16.5 14H19l2.5 2.5v2h-5");
}

</style>
