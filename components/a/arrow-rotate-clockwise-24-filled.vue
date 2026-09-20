<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apn7cqu0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-24-filled" /></template>
<style>
.apn7cqu0c {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 1 5.653 16H19a1 1 0 1 1 0 2h-4a1 1 0 0 1-1-1v-4a1 1 0 1 1 2 0v1.743A7 7 0 1 0 5 12a1 1 0 1 1-2 0a9 9 0 0 1 9-9m0 6a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 2a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
