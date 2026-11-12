<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qssp4abul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chapters-fill-round" /></template>
<style>
.qssp4abul {
  fill: currentColor;
  d: path("M7 2h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m2 4v8a1 1 0 0 0 1.555.832l6-4a1 1 0 0 0 0-1.664l-6-4A1 1 0 0 0 9 6M6 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm7 0a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Z");
}

</style>
