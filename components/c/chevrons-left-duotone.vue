<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lu-sdh82m"/><path class="b0q94rbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-left-duotone" /></template>
<style>
.b0q94rbrm {
  d: path("M18 17L13 12L18 7");
}

.lu-sdh82m {
  stroke-opacity: 0.4;
  d: path("M11 17L6 12L11 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
