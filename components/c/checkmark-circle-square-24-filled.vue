<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l52l52byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-circle-square-24-filled" /></template>
<style>
.l52l52byi {
  fill: currentColor;
  d: path("M8.5 16a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m3.78-9.22l-4 4a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 0 1 1.06-1.06l1.47 1.47l3.47-3.47a.75.75 0 1 1 1.06 1.06m8 6.94a.75.75 0 0 1 0 1.06l-4 4a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l1.47 1.47l3.47-3.47a.75.75 0 0 1 1.06 0M9.75 20v-3.091a8.4 8.4 0 0 0 1.5-.364V20c0 .966.784 1.75 1.75 1.75h7A1.75 1.75 0 0 0 21.75 20v-7A1.75 1.75 0 0 0 20 11.25h-3.455q.249-.724.364-1.5H20A3.25 3.25 0 0 1 23.25 13v7A3.25 3.25 0 0 1 20 23.25h-7A3.25 3.25 0 0 1 9.75 20");
}

</style>
