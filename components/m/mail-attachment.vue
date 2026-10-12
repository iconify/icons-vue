<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u7n6q4bzr"/><path class="hu0qff1um"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-attachment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hu0qff1um {
  d: path("m4.5 10.75l2.9 2.2a1.5 1.5 0 0 0 1.7 0l2.9-2.2m9.25-.75V5.25a2.5 2.5 0 0 0-5 0v7a1.25 1.25 0 0 0 2.5 0V6.5");
}

.u7n6q4bzr {
  width: 11px;
  height: 12px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

</style>
