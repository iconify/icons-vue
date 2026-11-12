<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8e1bqane"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chapters-fill-sharp" /></template>
<style>
.h8e1bqane {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm14.555 6.168l-6-4A1 1 0 0 0 9 6v8a1 1 0 0 0 1.555.832l6-4a1 1 0 0 0 0-1.664M6 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm7 0a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Z");
}

</style>
