<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e72kiv56z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drop-shadow-fill-round" /></template>
<style>
.e72kiv56z {
  fill: currentColor;
  d: path("M7 2h4a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m10 18a3 3 0 0 0 3-3V7a1 1 0 0 1 2 0v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a1 1 0 0 1 0-2Z");
}

</style>
