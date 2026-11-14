<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s75cpbcyq"/><path class="x_e0ncpft"/><path class="bn18w2o8y"/><path class="xo7-jkbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beat-maker" /></template>
<style>
.bn18w2o8y {
  fill: currentColor;
  d: path("M15.75 8.75h.5A1.75 1.75 0 0 1 18 10.5v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 14 11v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s75cpbcyq {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5M6 5.5h4.5");
}

.x_e0ncpft {
  d: path("M7.75 8.75h.5A1.75 1.75 0 0 1 10 10.5v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 6 11v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

.xo7-jkbrt {
  d: path("M7.75 15.5h.5A1.75 1.75 0 0 1 10 17.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 6 17.75v-.5a1.75 1.75 0 0 1 1.75-1.75m8 0h.5A1.75 1.75 0 0 1 18 17.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 14 17.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
