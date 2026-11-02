<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oss42b36t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-check-fill-sharp" /></template>
<style>
.oss42b36t {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm5.707 6.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414L13 10.586ZM4 9v11h11a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0");
}

</style>
