<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d7smd9b8i"/><path class="v5_ol6yqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breeze-outline-regular" /></template>
<style>
.d7smd9b8i {
  d: path("M2 8h13a3.5 3.5 0 1 0 -3.5 -3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v5_ol6yqz {
  d: path("M2 17h12a3.5 3.5 0 1 0 -3.5 3.5");
}

</style>
