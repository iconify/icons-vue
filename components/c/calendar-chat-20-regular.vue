<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nlw9lwblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-20-regular" /></template>
<style>
.nlw9lwblx {
  fill: currentColor;
  d: path("M5.5 16h3.707q.114.4.283.773L9.421 17H5.5A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5v4.1a5.5 5.5 0 0 0-1-.393V7H4v7.5A1.5 1.5 0 0 0 5.5 16m0-12A1.5 1.5 0 0 0 4 5.5V6h12v-.5A1.5 1.5 0 0 0 14.5 4zm5.063 12.682l-.544 1.789a.41.41 0 0 0 .51.51l1.79-.544a4.5 4.5 0 1 0-1.755-1.755M12.5 16a.5.5 0 0 1 0-1h2a.5.5 0 1 1 0 1zm0-3h4a.5.5 0 1 1 0 1h-4a.5.5 0 0 1 0-1");
}

</style>
