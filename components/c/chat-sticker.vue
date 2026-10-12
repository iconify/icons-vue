<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fros2nmyb"/><path class="k5jte4kml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-sticker" /></template>
<style>
.fros2nmyb {
  d: path("M2.75 6.25a2.5 2.5 0 0 1 2.5-2.5h9.45a1.5 1.5 0 0 1 1.06.44l5.05 5.05a1.5 1.5 0 0 1 .44 1.06v5.2a2.5 2.5 0 0 1-2.5 2.5H12.5L8 20.85a.77.77 0 0 1-1.25-.6v-2.5h-1.5a2.5 2.5 0 0 1-2.5-2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5jte4kml {
  d: path("M15.25 4.25V7a2.5 2.5 0 0 0 2.5 2.5h2.75m-13 2.75c1.75 1.5 4.75 1.5 6.5 0");
}

</style>
