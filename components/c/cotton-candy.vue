<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="anc7wbbys"/><path class="z1bek775o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cotton-candy" /></template>
<style>
.anc7wbbys {
  d: path("M6.75 12.25a2.5 2.5 0 0 1-.5-4.9A3 3 0 0 1 10.75 5a3.25 3.25 0 0 1 5.5 1.25a3 3 0 0 1 1.25 6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1bek775o {
  d: path("M9 9.5c1.5-1.25 4.5-1.25 6 0m-3 2.75v9");
}

</style>
