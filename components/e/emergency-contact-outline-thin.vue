<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eb5zxsbop"/><path class="mz4c5lb-h"/><path class="meft4rjfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:emergency-contact-outline-thin" /></template>
<style>
.eb5zxsbop {
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.meft4rjfc {
  d: path("M13.5 11a3.5 3.5 0 0 1 7 0");
}

.mz4c5lb-h {
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
