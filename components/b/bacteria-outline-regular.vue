<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ed5pr-bww"/><path class="wktcpfcga"/><path class="c1gddow5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bacteria-outline-regular" /></template>
<style>
.c1gddow5o {
  d: path("m8 17 -4 4");
}

.ed5pr-bww {
  d: path("m5 14 6 -6a4 4 0 0 1 6 6l-6 6a4 4 0 0 1 -6 -6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wktcpfcga {
  d: path("m17 11 4 -4");
}

</style>
