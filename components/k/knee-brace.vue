<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ncmd0y9gp"/><path class="ga0agwbgm"/><path class="qgm7y11xy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:knee-brace" /></template>
<style>
.ga0agwbgm {
  fill: currentColor;
  d: path("M18.25 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ncmd0y9gp {
  d: path("M9.5 7h4a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6 13.5v-3A3.5 3.5 0 0 1 9.5 7M8 2.5V7m7-4.5V7M8 17v4.5m7-4.5v4.5m4-17za1.25 1.25 0 0 1 1.25 1.25v12.5A1.25 1.25 0 0 1 19 19.5a1.25 1.25 0 0 1-1.25-1.25V5.75A1.25 1.25 0 0 1 19 4.5");
}

.qgm7y11xy {
  d: path("M9 10h5m-5 4h5");
}

</style>
