<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g7j-jsn8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chart-multiple-28-regular" /></template>
<style>
.g7j-jsn8g {
  fill: currentColor;
  d: path("M16.5 19a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-3 0v-4a1.5 1.5 0 0 1 1.5-1.5m4-2.5A1.5 1.5 0 0 1 22 18v6.5a1.5 1.5 0 0 1-3 0V18a1.5 1.5 0 0 1 1.5-1.5m4-3.5a1.5 1.5 0 0 1 1.5 1.5v10a1.5 1.5 0 0 1-3 0v-10a1.5 1.5 0 0 1 1.5-1.5M11.749 5.504c.69 0 1.251.558 1.251 1.25v4.496a2.25 2.25 0 0 0 2.25 2.25h4.496c.692 0 1.25.562 1.25 1.251v.022a9 9 0 0 1-.057.766a2.5 2.5 0 0 0-1.548.223q.065-.375.09-.762H15.25a3.75 3.75 0 0 1-3.75-3.75V7.019A7.499 7.499 0 1 0 14 21.727v1.546a9 9 0 1 1-2.273-17.77zM15.5 2a9 9 0 0 1 9 9a1 1 0 0 1-1 1h-7.75c-.69 0-1.25-.56-1.25-1.25V3a1 1 0 0 1 1-1m.5 8.5h6.981A7.5 7.5 0 0 0 16 3.519z");
}

</style>
