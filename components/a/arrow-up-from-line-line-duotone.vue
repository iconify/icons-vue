<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a8axvdbak"/><path class="tg58zp32w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-from-line-line-duotone" /></template>
<style>
.a8axvdbak {
  d: path("M20 21L4 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tg58zp32w {
  d: path("M12 16L12 3M16 7.375L12 3L8 7.375");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
