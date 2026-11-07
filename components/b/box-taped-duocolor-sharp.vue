<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1dr-uv8b"/><path class="zxavhbc9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-duocolor-sharp" /></template>
<style>
.g1dr-uv8b {
  stroke-opacity: 0.4;
  d: path("m7.5 4.222l9 4.445");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zxavhbc9h {
  d: path("m12 2l9 4.444v11.112L12 22l-9-4.444V6.444zM3 6.444l9 4.445l9-4.445m-9 4.445V22");
}

</style>
