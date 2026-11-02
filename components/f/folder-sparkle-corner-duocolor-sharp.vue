<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mxoqgwdnm"/><path class="hw-h4twqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-sparkle-corner-duocolor-sharp" /></template>
<style>
.hw-h4twqp {
  d: path("M12 6h9v2M8 20H3V4h7l2 2");
}

.mxoqgwdnm {
  stroke-opacity: 0.4;
  d: path("M17 13c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
