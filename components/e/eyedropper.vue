<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlv65k1_t"/><path class="r5kddd78e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eyedropper" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5kddd78e {
  d: path("M14.121 9.879za1.5 1.5 0 0 1 0 2.121l-4.378 4.378a1.5 1.5 0 0 1-.504.333l-1.482.592a.816.816 0 0 1-1.06-1.06l.592-1.482a1.5 1.5 0 0 1 .333-.504L12 9.879a1.5 1.5 0 0 1 2.121 0");
}

.vlv65k1_t {
  d: path("M18.718 5.282za2 2 0 0 1 0 2.829L16.95 9.879a2 2 0 0 1-2.829 0a2 2 0 0 1 0-2.829l1.768-1.768a2 2 0 0 1 2.829 0M11.293 7.05l5.657 5.657");
}

</style>
