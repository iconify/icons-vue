<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yfsk7t85l"/><path class="az5a16bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-line-duotone" /></template>
<style>
.az5a16bac {
  d: path("M18 10L12 4L6 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfsk7t85l {
  d: path("M12 20V4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
