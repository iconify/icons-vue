<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqpdxihwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-fill-round" /></template>
<style>
.zqpdxihwc {
  fill: currentColor;
  d: path("M10 7v4h4V7a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 10v4c0 1.27-.803 2.405-2 2.829V17a3 3 0 1 1-6 0v-4h-4v4a3 3 0 1 1-6 0v-.171A3 3 0 0 1 2 14v-4c0-1.27.803-2.405 2-2.829V7a3 3 0 1 1 6 0");
}

</style>
