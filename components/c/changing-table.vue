<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9tp09bad"/><path class="i2hd45oem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:changing-table" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2hd45oem {
  d: path("M4 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M13.75 5H18a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-4.25a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

.r9tp09bad {
  d: path("M4.5 9h15a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 10.5A1.5 1.5 0 0 1 4.5 9m.5 3v8.5M19 12v8.5");
}

</style>
