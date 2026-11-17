<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2kw8wbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-check-fill-sharp" /></template>
<style>
.h2kw8wbfa {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0v3h4a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Zm6-3a2 2 0 1 0-4 0v3h4Zm-5.293 8.293a.999.999 0 1 0-1.414 1.414l3 3a1 1 0 0 0 1.414 0l5-5a.999.999 0 1 0-1.414-1.414L11 16.586Z");
}

</style>
