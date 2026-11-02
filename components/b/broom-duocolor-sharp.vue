<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gilwoj1ah"/><path class="m37i7tclc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-duocolor-sharp" /></template>
<style>
.gilwoj1ah {
  stroke-opacity: 0.4;
  d: path("M12 3v9");
}

.m37i7tclc {
  d: path("M8 12h8l4 8H4zm2 8v-3m4 3v-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
