<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="az74cdzje"/><path clip-rule="evenodd" class="xj0jigu8t"/><path class="uhytr4bxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-terminal-duotone" /></template>
<style>
.az74cdzje {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 3.7909 3.7909 2 6 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uhytr4bxf {
  d: path("M7 11L10.0571 13.6204C10.1679 13.7154 10.2317 13.854 10.2317 14C10.2317 14.146 10.1679 14.2846 10.0571 14.3796L7 17M14 17L17 17");
}

.xj0jigu8t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7C8 7.5523 7.5523 8 7 8C6.4477 8 6 7.5523 6 7C6 6.4477 6.4477 6 7 6C7.5523 6 8 6.4477 8 7ZM12 7C12 7.5523 11.5523 8 11 8C10.4477 8 10 7.5523 10 7C10 6.4477 10.4477 6 11 6C11.5523 6 12 6.4477 12 7ZM16 7C16 7.5523 15.5523 8 15 8C14.4477 8 14 7.5523 14 7C14 6.4477 14.4477 6 15 6C15.5523 6 16 6.4477 16 7Z");
  stroke: none;
}

</style>
