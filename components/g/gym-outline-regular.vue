<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwufvfb8q"/><path class="veo4_yb-t"/><path class="mkaclw6aw"/><path class="fkf_gcbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gym-outline-regular" /></template>
<style>
.fkf_gcbra {
  d: path("M10 15h4");
}

.hwufvfb8q {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

.mkaclw6aw {
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.veo4_yb-t {
  d: path("M6 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
