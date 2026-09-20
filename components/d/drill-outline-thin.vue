<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nguhiybnr"/><path class="r411km12t"/><path class="ez1_3xbuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drill-outline-thin" /></template>
<style>
.ez1_3xbuo {
  d: path("M14 8h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nguhiybnr {
  d: path("M4 5h10v6H4Z");
}

.r411km12t {
  d: path("M6 11v9h4v-9");
}

</style>
