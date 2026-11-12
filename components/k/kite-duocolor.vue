<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mvv8hjb0d"/><path class="o2pyq20xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-duocolor" /></template>
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

.o2pyq20xd {
  d: path("m17 13l-4 4a1.414 1.414 0 0 1-2 0L3 9l9-6l9 6zm-5-9v13M4 9h16");
}

</style>
