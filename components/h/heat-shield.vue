<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q0te17dln"/><path class="seuj8i0tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0te17dln {
  d: path("M3 20q9-9 18 0Zm4.5-6.5Q6 11.25 7.5 9t0-4.5");
}

.seuj8i0tl {
  d: path("M12 12.5q-1.5-2.5 0-4.75T12 3m4.5 10.5q-1.5-2.25 0-4.5t0-4.5");
}

</style>
