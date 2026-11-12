<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvykynp5y"/><path class="uq006wbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-increase-duocolor" /></template>
<style>
.jvykynp5y {
  stroke-opacity: 0.4;
  d: path("m18 21l3-3l-3-3m3 3H3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uq006wbje {
  d: path("M7 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0Zm8 0a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM3 9h.01");
}

</style>
