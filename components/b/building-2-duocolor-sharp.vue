<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7lo4gz-o"/><path class="c_2oglksg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-duocolor-sharp" /></template>
<style>
.c_2oglksg {
  d: path("M3 20h18m-9 0V4H5v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7lo4gz-o {
  stroke-opacity: 0.4;
  d: path("M12 10.6L14 9l5 4v7");
}

</style>
