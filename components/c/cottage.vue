<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yoffmnbyb"/><path class="ikvuw6bzw"/><path class="jh-il49ab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cottage" /></template>
<style>
.ikvuw6bzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.25h.01");
}

.jh-il49ab {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25v-3.5a1.75 1.75 0 0 1 3.5 0v3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yoffmnbyb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.35v-8.2q0-.9.65-1.53l6.2-5.99q.65-.63 1.3 0l1.7 1.64Q15 6.9 15 6v-.6q0-.9.9-.9h.95q.9 0 .9.9v3.25q0 .9.65 1.53l.45.44q.65.63.65 1.53v8.2q0 .9-.9.9H5.4q-.9 0-.9-.9");
}

</style>
