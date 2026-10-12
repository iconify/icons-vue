<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="te9nqibxt"/><path class="f55t62bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lut-cube" /></template>
<style>
.f55t62bjh {
  d: path("m12.88 3.23l6.49 3.54q.88.48 0 .96l-6.49 3.54q-.88.48-1.76 0L4.63 7.73q-.88-.48 0-.96l6.49-3.54q.88-.48 1.76 0M12 11.75v9.5M3.75 12L12 16.5l8.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.te9nqibxt {
  d: path("m12.88 3.23l6.49 3.54q.88.48.88 1.48v7.5q0 1-.88 1.48l-6.49 3.54q-.88.48-1.76 0l-6.49-3.54q-.88-.48-.88-1.48v-7.5q0-1 .88-1.48l6.49-3.54q.88-.48 1.76 0");
}

</style>
