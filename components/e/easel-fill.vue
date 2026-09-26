<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z9lr1rbzg"/><path class="yp25-fb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:easel-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yp25-fb0x {
  d: path("M2 16L22 16M8 16L6.5 21M16 16L17.5 21M12 16L12 19");
}

.z9lr1rbzg {
  fill: currentColor;
  d: path("M6 2L18 2C19.6569 2 21 3.3431 21 5L21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16L3 5C3 3.3431 4.3431 2 6 2Z");
  stroke: none;
}

</style>
