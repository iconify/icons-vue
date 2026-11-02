<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xup5sqsvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-fill-sharp" /></template>
<style>
.xup5sqsvo {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H8v1h9a1 1 0 0 1 1 1v2h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1h-1a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h3v-1H7a1 1 0 0 1-1-1v-2H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h1Z");
}

</style>
