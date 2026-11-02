<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r1lsjwqka"/><path class="sonmiwbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:butterfly-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1lsjwqka {
  stroke-opacity: 0.4;
  d: path("M12 7v11");
}

.sonmiwbvs {
  d: path("M12 10c1.5-2.5 4.5-5 7-5c1.1 0 2 .9 2 2c0 3-1 5-5 7q3 .75 3 3c0 1.7-1.3 3-3 3c-2 0-3.5-.5-4-2m0-8c-1.5-2.5-4.5-5-7-5c-1.1 0-2 .9-2 2c0 3 1 5 5 7q-3 .75-3 3c0 1.7 1.3 3 3 3c2 0 3.5-.5 4-2");
}

</style>
