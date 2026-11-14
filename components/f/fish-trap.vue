<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ya_svtbtz"/><path class="e2hrhqosf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-trap" /></template>
<style>
.e2hrhqosf {
  d: path("M17.5 11c-1.5-2.5-5-2.5-6.5 0c1.5 2.5 5 2.5 6.5 0M11 11L9.5 9.5M11 11l-1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya_svtbtz {
  d: path("M3 20.5v-8a9 9 0 0 1 18 0v8Zm0-8l5 2m-5 6l5-3.25");
}

</style>
