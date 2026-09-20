<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crv4i00bu"/><path class="nfb4ipisv"/><path class="b603-acaz"/><path class="pqv-otbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:llm-trace-outline-regular" /></template>
<style>
.b603-acaz {
  d: path("M10 12h8");
}

.crv4i00bu {
  d: path("M4 3v18");
}

.nfb4ipisv {
  d: path("M7 7h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqv-otbrp {
  d: path("M13 17h8");
}

</style>
