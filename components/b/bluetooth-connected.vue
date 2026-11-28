<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z44g48bjr"/><path class="as22tbckp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-connected" /></template>
<style>
.as22tbckp {
  fill: currentColor;
  d: path("M7 12C7 12.5523 6.5523 13 6 13C5.4477 13 5 12.5523 5 12C5 11.4477 5.4477 11 6 11C6.5523 11 7 11.4477 7 12ZM19 12C19 12.5523 18.5523 13 18 13C17.4477 13 17 12.5523 17 12C17 11.4477 17.4477 11 18 11C18.5523 11 19 11.4477 19 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z44g48bjr {
  d: path("M7 7L17 17L12 22L12 2L17 7L7 17");
}

</style>
