<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km_-xmb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-fill-sharp" /></template>
<style>
.km_-xmb-s {
  fill: currentColor;
  d: path("M21.316 8.051a1 1 0 0 1 .131 1.843l-4.759 2.38l4.019 4.019a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-4.019-4.019l-2.38 4.759a1 1 0 0 1-1.843-.131l-6-18a1.001 1.001 0 0 1 1.265-1.265Z");
}

</style>
