<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_t5ec7az"/><path class="xyfugct1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:found-person" /></template>
<style>
.c_t5ec7az {
  d: path("M12 21.5c-4-4.5-7-8-7-12a7 7 0 0 1 14 0c0 4-3 7.5-7 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xyfugct1z {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 7c0-1.5 1-2.25 2.5-2.25s2.5.75 2.5 2.25");
}

</style>
