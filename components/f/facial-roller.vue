<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9y-apb4i"/><path class="mo0-fh8sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:facial-roller" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mo0-fh8sr {
  d: path("M6.5 5.25H5V8.5a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V5.25h-1.5M12 10.5V17m-1.5 0h3a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

.v9y-apb4i {
  d: path("M8.75 3h6.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-6.5A2.25 2.25 0 0 1 6.5 5.25A2.25 2.25 0 0 1 8.75 3");
}

</style>
