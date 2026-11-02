<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d9uxpcasu"/><path class="rb77lkb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-6-duocolor-round" /></template>
<style>
.d9uxpcasu {
  stroke-opacity: 0.4;
  d: path("M15 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 0v-4a3 3 0 0 1 3-3h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rb77lkb_u {
  d: path("M3 5v14m8-14v14m-8-7h8");
}

</style>
