<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ujsix8bue"/><path class="y8t0uccag"/><path class="soulwabnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hollow-log" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.soulwabnn {
  d: path("M16 10.75a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0M2.5 19.5h19");
}

.ujsix8bue {
  d: path("M17.5 4.75h-12q-3 0-3 6t3 6h12");
}

.y8t0uccag {
  d: path("M13.5 10.75a4 6 0 1 0 8 0a4 6 0 1 0-8 0");
}

</style>
