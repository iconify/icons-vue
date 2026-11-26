<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d0n8rdbjn"/><path class="cv5bz4iey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:curves-two-tone" /></template>
<style>
.cv5bz4iey {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3ZM3 18C12 18 12 6 21 6");
}

.d0n8rdbjn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L18 2C20.2092 2 22 3.7909 22 6L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7909 22 2 20.2092 2 18L2 6C2 3.7909 3.7909 2 6 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
