<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6aw85bah"/><path class="l7dxj4nrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breadboard-wires" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6aw85bah {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 8");
}

.l7dxj4nrm {
  d: path("M12 11c0-8 5-8 5 0M7 11h.01M12 11h.01M17 11h.01M7 14h.01M12 14h.01M17 14h.01M7 17h.01M12 17h.01M17 17h.01");
}

</style>
