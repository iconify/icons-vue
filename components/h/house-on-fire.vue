<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nt0tc9b7j"/><path class="q7-rvyr8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:house-on-fire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nt0tc9b7j {
  d: path("m8.03 6.03l3.69 3.69q.53.53.53 1.28v9.5q0 .75-.75.75h-8q-.75 0-.75-.75V11q0-.75.53-1.28l3.69-3.69q.53-.53 1.06 0");
}

.q7-rvyr8k {
  d: path("M6 21.25v-4a1.5 1.5 0 0 1 3 0v4m9.22-5.71a2.97 2.97 0 0 0 2.97-2.97c0-1.87-1.32-2.86-1.98-5.17c-.44 1.21-.99 1.76-1.65 2.31c-.22-.44-.44-.77-.77-1.1c-.99 1.1-1.54 2.2-1.54 3.96a2.97 2.97 0 0 0 2.97 2.97");
}

</style>
