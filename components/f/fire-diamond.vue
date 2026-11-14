<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezfuhbbdz"/><path class="gnk1ss02y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-diamond" /></template>
<style>
.ezfuhbbdz {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

.gnk1ss02y {
  d: path("M12 6.75c2.5 2.5 3.25 4.5 3.25 7a3.25 3.25 0 0 1-6.5 0c0-1.75.75-3 1.75-4c.25 1 .75 1.5 1.25 1.75c-.25-1.5-.25-3 .25-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
