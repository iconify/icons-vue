<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u23g4vxuk"/><path class="beuwu3f2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grafting-tape" /></template>
<style>
.beuwu3f2f {
  d: path("M10 18.5h11.5l-1.25-2.25H15.5M7 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u23g4vxuk {
  d: path("M2.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>
