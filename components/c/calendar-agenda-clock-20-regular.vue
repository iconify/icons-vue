<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="owfz7ubif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-20-regular" /></template>
<style>
.owfz7ubif {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0-7A2.5 2.5 0 0 1 17 5.5v4.1a5.5 5.5 0 0 0-1-.392V5.5A1.5 1.5 0 0 0 14.5 4h-9A1.5 1.5 0 0 0 4 5.5v9A1.5 1.5 0 0 0 5.5 16h3.708q.149.524.394 1H5.5A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm0 9a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H16a.5.5 0 0 0 0-1h-1v-1.5a.5.5 0 0 0-.5-.5m-5.292 1a5.5 5.5 0 0 0-.185 1H6.5a.5.5 0 0 1-.09-.992L6.5 13zm3.001-3.5a5.5 5.5 0 0 0-1.482 1H6.5a.5.5 0 0 1-.09-.992L6.5 9.5zM13.5 6a.5.5 0 0 1 .09.992L13.5 7h-7a.5.5 0 0 1-.09-.992L6.5 6z");
}

</style>
