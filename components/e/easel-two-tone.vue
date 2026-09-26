<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="esayqubgy"/><path class="l2qg27btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:easel-two-tone" /></template>
<style>
.esayqubgy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2L18 2C19.6569 2 21 3.3431 21 5L21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16L3 5C3 3.3431 4.3431 2 6 2Z");
  stroke: none;
}

.l2qg27btt {
  d: path("M6 3L18 3C19.1046 3 20 3.8954 20 5L20 16L4 16L4 5C4 3.8954 4.8954 3 6 3ZM2 16L22 16M8 16L6.5 21M16 16L17.5 21M12 16L12 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
