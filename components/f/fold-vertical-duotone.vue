<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-8mvnbqz"/><path class="i1svz3bwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fold-vertical-duotone" /></template>
<style>
.i1svz3bwg {
  d: path("M12 2L12 8M9 5L12 8L15 5M12 22L12 16M9 19L12 16L15 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y-8mvnbqz {
  stroke-opacity: 0.4;
  d: path("M5 12L19 12");
}

</style>
