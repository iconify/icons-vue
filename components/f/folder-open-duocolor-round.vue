<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbki_75ny"/><path class="w7e9ii9ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-duocolor-round" /></template>
<style>
.lbki_75ny {
  stroke-opacity: 0.4;
  d: path("M19 11v-1a4 4 0 0 0-4-4h-3l-2-2H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w7e9ii9ft {
  d: path("m5 20l2-6c.597-1.792 2.208-3 4-3h8c.984 0 1.492 1.524 1 3l-1 3c-.597 1.792-2.208 3-4 3z");
}

</style>
