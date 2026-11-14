<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjw7-2b9h"/><path class="i2aqyd29h"/><path class="j3m9ptx8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:log-pile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2aqyd29h {
  d: path("M7.75 8.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m-1.5 7.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.j3m9ptx8l {
  d: path("M10.5 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.wjw7-2b9h {
  d: path("M3.5 15.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m8.5 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

</style>
