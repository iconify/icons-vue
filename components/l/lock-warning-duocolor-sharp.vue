<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mvyles6td"/><path class="kskc15b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-warning-duocolor-sharp" /></template>
<style>
.kskc15b9j {
  d: path("M4 9h16v12H4Zm4 0V7a4 4 0 1 1 8 0v2");
}

.mvyles6td {
  stroke-opacity: 0.4;
  d: path("M12 12v3m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
