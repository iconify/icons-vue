<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="djjjy168r"/><path class="nuq-cfbcs"/><path class="ud48g0bnt"/><path class="guh-f-ylj"/><path class="c-vnm8iux"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-script-duotone-regular" /></template>
<style>
.c-vnm8iux {
  d: path("M15 12h3");
}

.djjjy168r {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.guh-f-ylj {
  d: path("M9.5 9.5 12 12l-2.5 2.5");
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuq-cfbcs {
  d: path("M2 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ud48g0bnt {
  d: path("M7.5 9.5 5 12l2.5 2.5");
}

</style>
