<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hkaf7kf2p"/><path class="iutbjoitp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:drop-half-bottom-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hkaf7kf2p {
  d: path("M208 144a80 80 0 0 1-160 0a101 101 0 0 1 1.3-16h157.4a101 101 0 0 1 1.3 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iutbjoitp {
  d: path("M174 47.75a254.2 254.2 0 0 0-41.45-38.3a8 8 0 0 0-9.18 0A254.2 254.2 0 0 0 82 47.75C54.51 79.32 40 112.6 40 144a88 88 0 0 0 176 0c0-31.4-14.51-64.68-42-96.25M128 26c14.16 11.1 56.86 47.74 68.84 94H59.16C71.14 73.76 113.84 37.12 128 26m0 190a72.08 72.08 0 0 1-72-72q0-4 .36-8h143.28q.36 4 .36 8a72.08 72.08 0 0 1-72 72");
}

</style>
