<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujh-70bha"/><path class="g_s1zftyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-horizontal-duocolor-round" /></template>
<style>
.g_s1zftyp {
  d: path("m7 15l3-3l-3-3m3 3H3m14-3l-3 3l3 3m-3-3h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujh-70bha {
  stroke-opacity: 0.4;
  d: path("M12 4v4m0 8v4");
}

</style>
