<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7cyu9biu"/><path class="qravvf8eg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-download-corner-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7cyu9biu {
  stroke-opacity: 0.4;
  d: path("m14 18l3 3l3-3m-3 3v-8");
}

.qravvf8eg {
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5l2 2");
}

</style>
