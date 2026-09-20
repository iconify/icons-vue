<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g2_r8-5ba"/><path class="p0br8kbxy"/><path class="khupvdbel"/><path class="x7qdjyb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-left-down-duotone-regular" /></template>
<style>
.g2_r8-5ba {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4H10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khupvdbel {
  d: path("M20 4H10v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0br8kbxy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7qdjyb5k {
  d: path("m5 15 5 5 5 -5");
}

</style>
