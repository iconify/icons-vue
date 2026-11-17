<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="muy7nugza"/><path class="rm-z7ybxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.muy7nugza {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6 4l12 4c1.107.369 1.738 1.631 1 2l-2 1c-.984.492-.984 2.016 0 3l2 2a1.415 1.415 0 0 1 0 2l-1 1a1.415 1.415 0 0 1-2 0l-2-2c-.984-.984-2.508-.984-3 0l-1 2c-.369.738-1.631.107-2-1L4 6a1.58 1.58 0 0 1 2-2");
}

.rm-z7ybxs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 2c1.107.369 1.738 1.631 1 2l-2 1c-.984.492-.984 2.016 0 3l2 2a1.414 1.414 0 0 1 0 2l-1 1a1.414 1.414 0 0 1-2 0l-2-2c-.984-.984-2.508-.984-3 0l-1 2c-.369.738-1.631.107-2-1L4 6c-.412-1.236.764-2.412 2-2z");
}

</style>
