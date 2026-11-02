<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbn7mxb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-fill" /></template>
<style>
.mbn7mxb0u {
  fill: currentColor;
  d: path("M14 3a2 2 0 0 1 2 2v6h3c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6a2 2 0 0 1-.424-.635c-.286-.69-.163-1.561.549-1.932c.18-.093.379-.141.582-.14h3V5a2 2 0 0 1 2-2Z");
}

</style>
