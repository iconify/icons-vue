<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bhew75bef"/><path class="pwhwi3oal"/><path class="i1quvubhf"/><path class="ndwyshb9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:boxing-duotone-regular" /></template>
<style>
.bhew75bef {
  fill: currentColor;
  d: path("M6 7c0 -3 3 -4 6 -4 4 0 7 3 7 7v3H8v-3c-1 0 -2 -1 -2 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i1quvubhf {
  d: path("M6 7c0 -3 3 -4 6 -4 4 0 7 3 7 7v3H8v-3c-1 0 -2 -1 -2 -3");
}

.ndwyshb9b {
  d: path("M8 16v4h11v-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pwhwi3oal {
  fill: currentColor;
  d: path("M8 16v4h11v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
