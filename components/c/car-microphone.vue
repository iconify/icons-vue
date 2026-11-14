<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d4ya0c-na"/><path class="ogeezkbok"/><path class="cp2dkbdnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-microphone" /></template>
<style>
.cp2dkbdnn {
  d: path("M15 20a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.d4ya0c-na {
  d: path("M8.5 2.5za3 3 0 0 1 3 3v4a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogeezkbok {
  d: path("M3 9.5a5.5 5.5 0 0 0 11 0M8.5 15v5M5 20h6.2m3.8 0h-1v-2a1 1 0 0 1 1-1l1.5-2.25h3L21 17a1 1 0 0 1 1 1v2h-1m-2 0h-2");
}

</style>
