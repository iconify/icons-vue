<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1hz_r7sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-gantt-fill-sharp" /></template>
<style>
.h1hz_r7sp {
  fill: currentColor;
  d: path("M4 4v15h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0m3 3h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m3 4h7a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2m10 4a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
