<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ay0o1u2ti"/><path class="bfdhz8vvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-duocolor" /></template>
<style>
.ay0o1u2ti {
  stroke-opacity: 0.4;
  d: path("M9 10V6a3 3 0 0 1 6 0v4");
}

.bfdhz8vvn {
  d: path("M4 12a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm7 2a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
