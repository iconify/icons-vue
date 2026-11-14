<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdolcobhl"/><path class="l39tgyb2f"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ico" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l39tgyb2f {
  d: path("m6.75 11l-2.5 3v3.5L7.5 15m3 3v3.5M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.sdolcobhl {
  d: path("M12.02 15H7.5C6.25 9.5 7 5 10.5 2.5c3.098 2.213 4.041 5.993 3.35 10.646m.4-2.146l1.152 1.383");
}

</style>
