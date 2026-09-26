<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="swg5p7vax"/><path class="m9587_b1g"/><path class="sp3ujwwyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-duotone" /></template>
<style>
.m9587_b1g {
  d: path("M12 8L12 3.5M2 14.5L4 14.5M22 14.5L20 14.5M9 12L9 13M15 12L15 13M9 17L15 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sp3ujwwyq {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5Z");
  stroke: none;
}

.swg5p7vax {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 7L17 7C19.2091 7 21 8.7909 21 11L21 18C21 20.2091 19.2091 22 17 22L7 22C4.7909 22 3 20.2091 3 18L3 11C3 8.7909 4.7909 7 7 7Z");
  stroke: none;
}

</style>
