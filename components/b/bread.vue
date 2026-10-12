<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vjn1mnp6f"/><path class="ex0b7lbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bread" /></template>
<style>
.ex0b7lbho {
  d: path("M8 18.25h8V9.9a1.65 1.65 0 0 0-.75-3.15h-6.5A1.65 1.65 0 0 0 8 9.9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjn1mnp6f {
  d: path("M6.5 20.75h11a1 1 0 0 0 1-1v-8.4a3.75 3.75 0 0 0-1.5-7.1H7a3.75 3.75 0 0 0-1.5 7.1v8.4a1 1 0 0 0 1 1");
}

</style>
