<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtukr91vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-fill-sharp" /></template>
<style>
.vtukr91vt {
  fill: currentColor;
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m4-7a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2H7a1 1 0 0 0-1 1Zm12 0a1 1 0 0 0-2 0v2h-2a1 1 0 0 0 0 2h3a1 1 0 0 0 1-1Z");
}

</style>
