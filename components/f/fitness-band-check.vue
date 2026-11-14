<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tl7abhenc"/><path class="c09svp7_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fitness-band-check" /></template>
<style>
.c09svp7_z {
  d: path("m10.25 12l1.25 1.25l2.25-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tl7abhenc {
  d: path("M12 5.5zA3.5 3.5 0 0 1 15.5 9v6a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 8.5 15V9A3.5 3.5 0 0 1 12 5.5m-2 0v-3h4v3m-4 13v3h4v-3");
}

</style>
