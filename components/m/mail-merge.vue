<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p67faabil"/><path class="b73-47b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-merge" /></template>
<style>
.b73-47b0k {
  d: path("m6.5 14l4.1 2.65c.85.55 1.95.55 2.8 0L17.5 14M5.75 2.75C5.75 5 12 4 12 6v3.5m6.25-6.75C18.25 5 12 4 12 6M9.75 7.25L12 9.5l2.25-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p67faabil {
  width: 18.5px;
  height: 9.25px;
  x: 2.75px;
  y: 11px;
  rx: 2.5px;
}

</style>
