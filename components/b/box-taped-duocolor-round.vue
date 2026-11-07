<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1dr-uv8b"/><path class="aowv0qx_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-duocolor-round" /></template>
<style>
.aowv0qx_w {
  d: path("M21 12v4.313a2 2 0 0 1-1.114 1.793l-7 3.457a2 2 0 0 1-1.772 0l-7-3.457A2 2 0 0 1 3 16.313V7.687a2 2 0 0 1 1.114-1.793l7-3.457a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687zM3.32 6.602L12 10.89l8.68-4.287M12 10.89v10.88");
}

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

</style>
