<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r6has18fi"/><path class="gzur7ibuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemical-bottle" /></template>
<style>
.gzur7ibuz {
  d: path("M10 13.5h4a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 17v-2a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6has18fi {
  d: path("M10 6.5V8l-4.5 3v8.5a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V11L14 8V6.5m-3.25-4h2.5A1.75 1.75 0 0 1 15 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 4.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
