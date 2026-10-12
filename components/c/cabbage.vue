<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocuvw3b0n"/><path class="sy7_du0sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabbage" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocuvw3b0n {
  d: path("M7.6 7.4a5 5 0 0 1 8.8 0c1.5-1 3.5-1.2 4.5-.4c.7.9.1 2-.5 2.4c.9 1 1 2.6.1 3.5c.7 1.5.1 3.3-1.4 3.9c-.5 2.6-3.5 4.2-7.1 4.2s-6.6-1.6-7.1-4.2c-1.5-.6-2.1-2.4-1.4-3.9c-.9-.9-.8-2.5.1-3.5C3 9 2.4 7.9 3.1 7c1-.8 3-.6 4.5.4");
}

.sy7_du0sl {
  d: path("M7.6 7.4C8 12.75 9.5 17.75 12 21m4.4-13.6C16 12.75 14.5 17.75 12 21");
}

</style>
