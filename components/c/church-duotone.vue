<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qwg_9ccvd"/><path class="p2uayccez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p2uayccez {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21V11l4-4l4 4v10m-8-8l-2 1c-1.226.613-2 1.387-2 2v3a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-3c0-.613-.774-1.387-2-2l-2-1M12 3v4m-2-2h4");
}

.qwg_9ccvd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 13v-2l4-4l4 4v2l2 1c.651.326 1.999 1.15 2 2v3a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-3c.001-.85 1.349-1.674 2-2Z");
}

</style>
