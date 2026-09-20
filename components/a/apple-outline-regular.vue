<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujmlr05oy"/><path class="bpf3snbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:apple-outline-regular" /></template>
<style>
.bpf3snbqm {
  d: path("M12 9V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujmlr05oy {
  d: path("M12 9c-3 -4 -8 -2 -8 4 0 5 4 8 8 6 4 2 8 -1 8 -6 0 -6 -5 -8 -8 -4");
}

</style>
