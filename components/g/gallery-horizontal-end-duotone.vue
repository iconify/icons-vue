<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qkqlybmds"/><path class="a2wt9tb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-end-duotone" /></template>
<style>
.a2wt9tb9c {
  d: path("M7 5L7 19M3 7L3 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qkqlybmds {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2L19 2C20.65685 2 22 3.34315 22 5L22 19C22 20.65685 20.65685 22 19 22L13 22C11.34315 22 10 20.65685 10 19L10 5C10 3.34315 11.34315 2 13 2Z");
  stroke: none;
}

</style>
