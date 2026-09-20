<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mddrthmzf"/><path class="xa0iemevq"/><path class="e9i5dwbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distribution-shift-outline-thin" /></template>
<style>
.e9i5dwbzy {
  d: path("m10.5 13.5 3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mddrthmzf {
  d: path("M3 16a4 4 0 0 1 8 0");
}

.xa0iemevq {
  d: path("M13 12a4 4 0 0 1 8 0");
}

</style>
