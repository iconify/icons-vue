<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od19jzbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-fill-round" /></template>
<style>
.od19jzbtk {
  fill: currentColor;
  d: path("M14.333 16H13v2h5a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1h5v-2H9.667a4 4 0 0 1-4-4V9.028a4 4 0 0 1 1.366-3.01l2.333-2.042a4 4 0 0 1 5.268 0l2.333 2.042a4 4 0 0 1 1.366 3.01V12a4 4 0 0 1-4 4");
}

</style>
