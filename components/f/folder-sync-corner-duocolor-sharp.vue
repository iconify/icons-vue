<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kotve_3_b"/><path class="hw-h4twqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-sync-corner-duocolor-sharp" /></template>
<style>
.hw-h4twqp {
  d: path("M12 6h9v2M8 20H3V4h7l2 2");
}

.kotve_3_b {
  stroke-opacity: 0.4;
  d: path("M21 19a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-7a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
