<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cg74vqa3v"/><path class="t_zwwrqor"/><path class="dgkag0bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atom-model" /></template>
<style>
.cg74vqa3v {
  d: path("M5.25 5.25a9.5 4 45 1 1 13.5 13.5a9.5 4 45 1 1-13.5-13.5");
}

.dgkag0bpp {
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.25 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_zwwrqor {
  d: path("M18.75 5.25a9.5 4-45 1 1-13.5 13.5a9.5 4-45 1 1 13.5-13.5");
}

</style>
