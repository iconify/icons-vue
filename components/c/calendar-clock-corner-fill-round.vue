<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbmbd51qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner-fill-round" /></template>
<style>
.gbmbd51qt {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1.099a5.01 5.01 0 0 1 3.607 2.954c.261.616.395 1.278.393 1.947a1 1 0 0 1-1 1H5v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H8a5 5 0 0 1-5-5V9a5.01 5.01 0 0 1 4-4.901Zm3 14a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m5-2v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
