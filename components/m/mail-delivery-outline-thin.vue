<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5oa6epzy"/><path class="yqiq35tbk"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-delivery-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5oa6epzy {
  d: path("M6 3v8h12V3Z");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.yqiq35tbk {
  d: path("m6 3 5 5 5 -5");
}

</style>
