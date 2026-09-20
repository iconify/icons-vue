<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cacmi2bmi"/><path class="ffipo4b5s"/><path class="mut__fbgb"/><path class="c8uh2gw9u"/><path class="krno6ds-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-file-outline-regular" /></template>
<style>
.c8uh2gw9u {
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.ffipo4b5s {
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.krno6ds-i {
  d: path("M13 15h3");
}

.mut__fbgb {
  d: path("M13 11h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
