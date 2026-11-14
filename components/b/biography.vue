<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="owj-6e7wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biography" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

.owj-6e7wn {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5m-9-9.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.5 6c0-1.75 1.75-2.5 3.75-2.5s3.75.75 3.75 2.5");
}

</style>
