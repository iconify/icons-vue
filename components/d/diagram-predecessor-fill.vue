<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6eejabpo"/><path class="g_8sig3wa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-predecessor-fill" /></template>
<style>
.g_8sig3wa {
  d: path("M12 18.5L17 18.5C17.5523 18.5 18 18.0523 18 17.5L18 12M16 14L18 12L20 14");
}

.k6eejabpo {
  fill: currentColor;
  d: path("M4 15L11 15C12.1046 15 13 15.8954 13 17L13 20C13 21.1046 12.1046 22 11 22L4 22C2.8954 22 2 21.1046 2 20L2 17C2 15.8954 2.8954 15 4 15ZM4 2L20 2C21.1046 2 22 2.8954 22 4L22 7C22 8.1046 21.1046 9 20 9L4 9C2.8954 9 2 8.1046 2 7L2 4C2 2.8954 2.8954 2 4 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
