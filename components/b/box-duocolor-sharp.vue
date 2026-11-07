<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbr6jfbcq"/><path class="pqg7h7bjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqg7h7bjb {
  d: path("m12 2l9 4.444v11.112L12 22l-9-4.444V6.444z");
}

.qbr6jfbcq {
  stroke-opacity: 0.4;
  d: path("m3 6.444l9 4.445l9-4.445m-9 4.445V22");
}

</style>
