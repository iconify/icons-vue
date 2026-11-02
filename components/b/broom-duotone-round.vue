<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wee8f2bib"/><path class="w0_2kdb9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w0_2kdb9e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H6c-.919 0-1.46-1.081-1-2l2-4c.613-1.226 1.387-2 2-2h6c.613 0 1.387.774 2 2l2 4c.46.919-.081 2-1 2zm-2 0v-3m4 3v-3M12 3v9");
}

.wee8f2bib {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m4.106 17.553l2-4C6.643 12.478 7.652 11.001 9 11h6c1.348.001 2.357 1.478 2.894 2.553l2 4c.181.356.274.75.273 1.149C20.164 19.924 19.265 21 18 21H6c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149");
}

</style>
