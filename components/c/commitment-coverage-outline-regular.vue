<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="t-y1ijbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:commitment-coverage-outline-regular" /></template>
<style>
.nnzlfsekh {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t-y1ijbfb {
  d: path("M9 9h6v3l-3 3 -3 -3Z");
}

.teszqoqtj {
  d: path("M5.5 10.5v3");
}

.zqsgc7abe {
  d: path("M18.5 10.5v3");
}

</style>
