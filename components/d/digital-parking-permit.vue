<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="holombb2f"/><path class="fcsl4vbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-parking-permit" /></template>
<style>
.fcsl4vbyw {
  d: path("M10 15V6.5h2.5a2.5 2.5 0 0 1 0 5H10m.5 7.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.holombb2f {
  d: path("M9.875 2h4.25A4.375 4.375 0 0 1 18.5 6.375v11.25A4.375 4.375 0 0 1 14.125 22h-4.25A4.375 4.375 0 0 1 5.5 17.625V6.375A4.375 4.375 0 0 1 9.875 2");
}

</style>
