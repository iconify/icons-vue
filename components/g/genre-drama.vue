<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgcgztbgg"/><path class="k-pz0ec8y"/><path class="zlja6ihoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-drama" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-pz0ec8y {
  d: path("M9.5 9.5h12v6a6 6 0 0 1-12 0ZM5 6.5l2-.75m3 0l2 .75m.25 6.5h2m2.5 0h2");
}

.sgcgztbgg {
  d: path("M14.5 9.5v-7h-12v6a6 6 0 0 0 7 6");
}

.zlja6ihoc {
  d: path("M12.5 16.5q3 3 6 0");
}

</style>
