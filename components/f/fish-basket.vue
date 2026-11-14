<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gi09erb1h"/><path class="hp4xdfb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-basket" /></template>
<style>
.gi09erb1h {
  d: path("M4 11h16l-1.5 8.5q-.25 1.5-2 1.5h-9q-1.75 0-2-1.5Zm-.5 0a8.5 8.5 0 0 1 17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp4xdfb_w {
  d: path("m11 11l.5-1.5l-2.5-3q3 1.5 6 0l-2.5 3L13 11m-8 4.75h14");
}

</style>
