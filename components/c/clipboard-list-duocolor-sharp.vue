<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r-z4zvetq"/><path class="y7n4sgyet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-list-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r-z4zvetq {
  stroke-opacity: 0.4;
  d: path("M9 12h.01M9 16h.01M12 12h3m-3 4h3");
}

.y7n4sgyet {
  d: path("M9 5H5v16h14V5h-4M9 5V3h6v2M9 5v2h6V5");
}

</style>
