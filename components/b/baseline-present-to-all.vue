<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq_t3-bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-present-to-all" /></template>
<style>
.vq_t3-bzj {
  fill: currentColor;
  d: path("M21 3H3c-1.11 0-2 .89-2 2v14c0 1.11.89 2 2 2h18c1.11 0 2-.89 2-2V5c0-1.11-.89-2-2-2m0 16.02H3V4.98h18zM10 12H8l4-4l4 4h-2v4h-4z");
}

</style>
