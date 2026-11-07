<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r4mf2tyqa"/><path class="uy8ki_b5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r4mf2tyqa {
  stroke-opacity: 0.4;
  d: path("M3.32 6.602L12 10.89l8.68-4.287M12 10.89v10.88");
}

.uy8ki_b5h {
  d: path("M21 12v4.313a2 2 0 0 1-1.114 1.793l-7 3.457a2 2 0 0 1-1.772 0l-7-3.457A2 2 0 0 1 3 16.313V7.687a2 2 0 0 1 1.114-1.793l7-3.457a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687z");
}

</style>
