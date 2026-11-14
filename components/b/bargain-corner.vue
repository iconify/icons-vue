<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wl672wo-l"/><path class="rgltw1bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bargain-corner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rgltw1bze {
  d: path("m14.755 7.575l.474.625a1.5 1.5 0 0 0 1.399.58l.778-.107a1.26 1.26 0 0 1 1.421 1.421l-.107.778a1.5 1.5 0 0 0 .58 1.399l.625.474a1.26 1.26 0 0 1 0 2.01l-.625.474a1.5 1.5 0 0 0-.58 1.399l.107.778a1.26 1.26 0 0 1-1.421 1.421l-.778-.107a1.5 1.5 0 0 0-1.399.58l-.474.625a1.26 1.26 0 0 1-2.01 0l-.474-.625a1.5 1.5 0 0 0-1.399-.58l-.778.107a1.26 1.26 0 0 1-1.421-1.421l.107-.778a1.5 1.5 0 0 0-.58-1.399l-.625-.474a1.26 1.26 0 0 1 0-2.01l.625-.474a1.5 1.5 0 0 0 .58-1.399l-.107-.778a1.26 1.26 0 0 1 1.421-1.421l.778.107a1.5 1.5 0 0 0 1.399-.58l.474-.625a1.26 1.26 0 0 1 2.01 0M11.25 16.25l5-5m-4.75.25h.01M16 16h.01");
}

.wl672wo-l {
  d: path("M3 21.5V3h18.5");
}

</style>
