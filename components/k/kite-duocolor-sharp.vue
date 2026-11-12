<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mvv8hjb0d"/><path class="xcaedubkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-duocolor-sharp" /></template>
<style>
.mvv8hjb0d {
  stroke-opacity: 0.4;
  d: path("M12 18c0 3 5 3 7 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xcaedubkk {
  d: path("m12 3l9 6l-9 9l-9-9zm0 0v15M3 9h18");
}

</style>
