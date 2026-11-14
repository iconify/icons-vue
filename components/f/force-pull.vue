<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j0kn9zb3w"/><path class="aqhhxbb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:force-pull" /></template>
<style>
.aqhhxbb6z {
  d: path("m18 9l3 3l-3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0kn9zb3w {
  d: path("M6 7h2a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 8 17H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 7m5.5 5c2.25 2.5 4-2.5 6.25 0H21");
}

</style>
