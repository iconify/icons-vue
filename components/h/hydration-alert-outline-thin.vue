<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_bq1yb3z"/><path class="ha190wb6v"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hydration-alert-outline-thin" /></template>
<style>
.ha190wb6v {
  d: path("M10 8V4h4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_bq1yb3z {
  d: path("M8 8v12h8V8Z");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

</style>
