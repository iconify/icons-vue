<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8b23fbyc"/><path class="kwy3ktbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-duocolor-sharp" /></template>
<style>
.d8b23fbyc {
  stroke-opacity: 0.4;
  d: path("M4 3v18");
}

.kwy3ktbhr {
  d: path("M8 4h12v6H8Zm0 10h8v6H8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
