<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugca6mbad"/><path class="d9rsgr4ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:files-grid" /></template>
<style>
.d9rsgr4ju {
  d: path("M8.25 2.75h7.5l4.5 4.5v10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ugca6mbad {
  d: path("M12.25 5.75h-6a2.5 2.5 0 0 0-2.5 2.5v10.5a2.5 2.5 0 0 0 2.5 2.5h7.5a2.5 2.5 0 0 0 2.5-2.5v-9Z");
}

</style>
