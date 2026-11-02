<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5w3hk87x"/><path class="msnx-d8eh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-low-duocolor-sharp" /></template>
<style>
.b5w3hk87x {
  stroke-opacity: 0.4;
  d: path("M6 10v4");
}

.msnx-d8eh {
  d: path("M3 7h15v10H3Zm18 3v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
