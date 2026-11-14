<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9iuj0bdx"/><path class="d92mcwbep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-pressure-test" /></template>
<style>
.d92mcwbep {
  d: path("M12.25 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM2.5 8.5L5 10m-2.5 2H5m-2.5 3.5L5 14");
}

.p9iuj0bdx {
  d: path("M7.5 12c2.5-4.5 11-4.5 14 0c-3 4.5-11.5 4.5-14 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
