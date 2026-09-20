<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="prp2-6bhy"/><path class="apfnny4vx"/><path class="h94i1-bcl"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jungle-outline-regular" /></template>
<style>
.apfnny4vx {
  d: path("M12 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.h94i1-bcl {
  d: path("M6.5 20.5c0 -5.4 3.6 -9 9 -9 0 5.4 -3.6 9 -9 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.prp2-6bhy {
  d: path("M2.5 12.5c0 -5.4 3.6 -9 9 -9 0 5.4 -3.6 9 -9 9");
}

</style>
