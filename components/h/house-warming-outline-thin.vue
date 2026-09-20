<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsz3y4a_c"/><path class="u-niy3p1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-warming-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsz3y4a_c {
  d: path("M4 19v-7l7 -7 7 7v7Z");
}

.u-niy3p1t {
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
}

</style>
