<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="shd7-wbsb"/><path class="lw-jkob5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gold-set-outline-regular" /></template>
<style>
.lw-jkob5l {
  d: path("M12 6.5v4");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shd7-wbsb {
  d: path("M9 8.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
