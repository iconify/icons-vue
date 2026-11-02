<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw5cubcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-scatter-fill-sharp" /></template>
<style>
.qw5cubcmh {
  fill: currentColor;
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0ZM15 6a2 2 0 1 1 3.999-.001A2 2 0 0 1 15 6m-4 5a2 2 0 1 1 3.999-.001A2 2 0 0 1 11 11m6 3a2 2 0 1 1 3.999-.001A2 2 0 0 1 17 14M6 15a2 2 0 1 1 3.999-.001A2 2 0 0 1 6 15");
}

</style>
