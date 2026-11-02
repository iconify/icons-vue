<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5une0p8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-exit-bulk" /></template>
<style>
.v5une0p8v {
  fill: currentColor;
  d: path("M6 7a1 1 0 0 0 1-1V3a1 1 0 0 1 2 0v3a3 3 0 0 1-3 3H3a1 1 0 0 1 0-2Zm11-1a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2h-3a3 3 0 0 1-3-3V3a1 1 0 0 1 2 0ZM7 18a.997.997 0 0 0-1-1H3a1 1 0 0 1 0-2h3a3 3 0 0 1 3 3v3a1 1 0 0 1-2 0Zm11-1a1 1 0 0 0-1 1v3a1 1 0 0 1-2 0v-3a3 3 0 0 1 3-3h3a1 1 0 0 1 0 2Z");
}

</style>
