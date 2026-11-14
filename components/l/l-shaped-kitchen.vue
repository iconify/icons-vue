<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlaaxj_te"/><path class="jzo90zgrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:l-shaped-kitchen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlaaxj_te {
  d: path("M2.5 2.5h19V12H12v9.5H2.5Z");
}

.jzo90zgrf {
  d: path("M5.25 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
