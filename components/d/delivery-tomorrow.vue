<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wps9rnbhp"/><path class="qadjfe5cf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-tomorrow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qadjfe5cf {
  d: path("m2.5 13.75l6 3l6-3m-6 3v4.5");
}

.wps9rnbhp {
  d: path("m8.5 10.75l6 3v4.5l-6 3l-6-3v-4.5ZM12.25 7A4.25 4.25 0 1 0 16 3.25A3 3 0 0 1 12.25 7");
}

</style>
