<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo1q_kb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-fill-sharp" /></template>
<style>
.fo1q_kb2d {
  fill: currentColor;
  d: path("M7 8V7a5 5 0 0 1 10 0v1h3a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Zm8-1a3 3 0 1 0-6 0v1h6Zm-4 8.733V17a1 1 0 0 0 2 0v-1.267a2.001 2.001 0 1 0-2 0");
}

</style>
