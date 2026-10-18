<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znr_ixbzl"/><path class="v3-6btben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-panel-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v3-6btben {
  d: path("M6.4286 4L3 8L6.4286 12M11 4L14.4286 8L11 12");
}

.znr_ixbzl {
  stroke-opacity: 0.4;
  d: path("M18 4C19.6569 4 21 5.3431 21 7L21 17C21 18.6569 19.6569 20 18 20L6 20C4.3431 20 3 18.6569 3 17L3 16");
}

</style>
