<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cgwbwtp3a"/><path class="kcxs7db4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-check-duocolor-sharp" /></template>
<style>
.cgwbwtp3a {
  stroke-opacity: 0.4;
  d: path("m8 15l3 3l5-5");
}

.kcxs7db4r {
  d: path("M4 10h16v11H4Zm5 0V6a3 3 0 0 1 6 0v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
