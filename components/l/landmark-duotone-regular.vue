<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fix8plbog"/><path class="u5jltjbuw"/><path class="kakiz1beo"/><path class="mjsa21byd"/><path class="ok9ioqb8x"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landmark-duotone-regular" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.fix8plbog {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 17V7l4 -4 4 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kakiz1beo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mjsa21byd {
  d: path("M8 17V7l4 -4 4 4v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.u5jltjbuw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
