<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xp_g-3-3v"/><path class="iv_t2mbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv_t2mbnq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11H7c-.919 0-1.46-1.081-1-2l2-4c.613-1.226 1.387-2 2-2h4c.613 0 1.387.774 2 2l2 4c.46.919-.081 2-1 2zm0 0v6m-4 2a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4h-4a2 2 0 0 1-2-2");
}

.xp_g-3-3v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149l2-4C7.643 3.478 8.652 2.001 10 2h4c1.348.001 2.357 1.478 2.894 2.553l2 4c.181.356.274.75.273 1.149C19.164 10.924 18.265 12 17 12Zm3 4h4a3 3 0 1 1 0 6h-4a3 3 0 1 1 0-6");
}

</style>
