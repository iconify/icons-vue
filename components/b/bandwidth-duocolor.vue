<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="knl92tmrp"/><path class="xs6yp0hje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandwidth-duocolor" /></template>
<style>
.knl92tmrp {
  stroke-opacity: 0.4;
  d: path("M6 12h12M9 9l-3 3l3 3m6-6l3 3l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xs6yp0hje {
  d: path("M3 5h18M3 19h18");
}

</style>
