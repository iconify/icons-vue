<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm7_wrumk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-lock-corner-fill-round" /></template>
<style>
.vm7_wrumk {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1.099a5.01 5.01 0 0 1 3.607 2.954c.261.616.395 1.278.393 1.947a1 1 0 0 1-1 1H5v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H8a5 5 0 0 1-5-5V9a5.01 5.01 0 0 1 4-4.901V3a1 1 0 0 1 2 0Zm13 14v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829V15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18m-6-3h2a1 1 0 0 0-2 0m-2 3v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1");
}

</style>
