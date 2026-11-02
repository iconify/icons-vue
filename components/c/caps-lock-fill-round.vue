<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1c6mui4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caps-lock-fill-round" /></template>
<style>
.m1c6mui4u {
  fill: currentColor;
  d: path("M13 18h-2a3 3 0 0 1-3-3v-2a.997.997 0 0 0-1-1H6c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l6-6a2.414 2.414 0 0 1 3.414 0l6 6c.311.311.456.752.382 1.186C19.928 11.428 18.898 12 18 12h-1a.997.997 0 0 0-1 1v2a3 3 0 0 1-3 3m2 4H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

</style>
