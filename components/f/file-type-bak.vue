<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydzt7abec"/><path class="c05z0mtsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-bak" /></template>
<style>
.c05z0mtsz {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("M19.57 9.17a10 10 0 0 1 7.37 3.04a10 10 0 0 1 3.04 7.37a10 10 0 0 1-3.03 7.37a10 10 0 0 1-7.38 3.03a10 10 0 0 1-6.34-2.17l1.63-1.62a8.3 8.3 0 0 0 4.71 1.46a8.05 8.05 0 0 0 8.08-8.07a8.05 8.05 0 0 0-8.08-8.08a8.05 8.05 0 0 0-8.08 8.08h3.47l-4.66 4.6l-4.6-4.6h3.46a10 10 0 0 1 3.04-7.37a10 10 0 0 1 7.37-3.04");
}

.ydzt7abec {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M19.16 2.02H4.76v26.15h20.55v-20ZM6.63 26.3V3.9h11.2v5.6h5.61v16.8Z");
}

</style>
