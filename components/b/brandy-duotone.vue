<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ehq57rbvh"/><path class="y4d25uyog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:brandy-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ehq57rbvh {
  d: path("M216 88a88 88 0 0 1-176 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y4d25uyog {
  d: path("M224 88a95.63 95.63 0 0 0-15.53-52.37a8 8 0 0 0-6.7-3.63H54.23a8 8 0 0 0-6.7 3.63A95.63 95.63 0 0 0 32 88a96.12 96.12 0 0 0 88 95.66V216H88a8 8 0 0 0 0 16h80a8 8 0 0 0 0-16h-32v-32.34A96.12 96.12 0 0 0 224 88M58.7 48h138.6a79.5 79.5 0 0 1 10.3 32H48.4a79.5 79.5 0 0 1 10.3-32M128 168a80.11 80.11 0 0 1-79.6-72h159.2a80.11 80.11 0 0 1-79.6 72");
}

</style>
