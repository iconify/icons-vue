<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxfg33b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:corner-radius-fill" /></template>
<style>
.sxfg33b8p {
  fill: currentColor;
  d: path("M2 17C2 8.716 8.716 2 17 2h4a1 1 0 0 1 0 2h-4C9.82 4 4 9.82 4 17v4a1 1 0 0 1-2 0ZM2 5V3a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2H4v1a1 1 0 0 1-2 0");
}

</style>
