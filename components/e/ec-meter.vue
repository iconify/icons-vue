<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hoaw4vt8e"/><path class="k94hs-w_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ec-meter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoaw4vt8e {
  d: path("M7 2.5h2A3.5 3.5 0 0 1 12.5 6v5A3.5 3.5 0 0 1 9 14.5H7A3.5 3.5 0 0 1 3.5 11V6A3.5 3.5 0 0 1 7 2.5m1 12v7");
}

.k94hs-w_b {
  d: path("M7.75 5.25h.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M18 13.5c1.5 1.75 3 3.5 3 5a3 3 0 0 1-6 0c0-1.5 1.5-3.25 3-5");
}

</style>
