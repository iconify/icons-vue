<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cel-h2bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-exclamation-20-filled" /></template>
<style>
.cel-h2bde {
  fill: currentColor;
  d: path("M3 5a3 3 0 0 1 6 0c0 2.25-.788 5.214-1.224 6.69A1.84 1.84 0 0 1 6 13c-.811 0-1.542-.52-1.776-1.315C3.789 10.204 3 7.227 3 5m1 11a2 2 0 1 1 4 0a2 2 0 0 1-4 0M15 3.707V17.5a.5.5 0 0 1-1 0V3.707l-2.146 2.147a.5.5 0 0 1-.708-.708l3-3a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708z");
}

</style>
