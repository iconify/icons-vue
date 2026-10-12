<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxli-nb_m"/><path class="wldf59bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-flip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qxli-nb_m {
  d: path("M3.25 9.25a2 2 0 0 1 2-2h2.1l1.1-1.85a1.5 1.5 0 0 1 1.3-.75h4.5a1.5 1.5 0 0 1 1.3.75l1.1 1.85h2.1a2 2 0 0 1 2 2v8.5a2.5 2.5 0 0 1-2.5 2.5H5.75a2.5 2.5 0 0 1-2.5-2.5Z");
}

.wldf59bdw {
  d: path("M8.75 13a3.25 3.25 0 0 1 5.9-1.9m.6 2.4a3.25 3.25 0 0 1-5.9 1.9M14.9 9v2.25h-2.25m-3.55 6.5V15.5h2.25");
}

</style>
