<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xlwvpo0fs"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="rjnb3gzmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-area-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.rjnb3gzmu {
  d: path("m7 14 3 -3 4 4 6 -6v8H7Z");
}

.xlwvpo0fs {
  fill: currentColor;
  d: path("m7 14 3 -3 4 4 6 -6v8H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
