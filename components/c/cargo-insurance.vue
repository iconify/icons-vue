<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0juqr4ut"/><rect class="mpvv80bmu"/><path class="h4nexvb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-insurance" /></template>
<style>
.f0juqr4ut {
  d: path("M11.5 2.9a1.5 1.5 0 0 1 1 0l6 2.2a1.5 1.5 0 0 1 1 1.4v5c0 4.75-3.25 8.25-7.5 9.75c-4.25-1.5-7.5-5-7.5-9.75v-5a1.5 1.5 0 0 1 1-1.4Z");
}

.h4nexvb_h {
  d: path("M12 9v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpvv80bmu {
  width: 6.5px;
  height: 6px;
  x: 8.75px;
  y: 9px;
  rx: 0.75px;
}

</style>
