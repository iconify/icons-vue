<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rpk9jeb_i"/><path class="b80eh0awx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-duocolor-sharp" /></template>
<style>
.b80eh0awx {
  d: path("M10 11h7v10H3V9h5z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rpk9jeb_i {
  stroke-opacity: 0.4;
  d: path("M7 5V3h5l2 2m0 0h7v10");
}

</style>
