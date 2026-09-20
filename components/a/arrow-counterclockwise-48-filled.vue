<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tatnxz5su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-48-filled" /></template>
<style>
.tatnxz5su {
  fill: currentColor;
  d: path("M39 24c0-8.284-6.716-15-15-15c-3.938 0-7.52 1.516-10.198 4H17.5a1.5 1.5 0 0 1 0 3h-7A1.5 1.5 0 0 1 9 14.5v-7a1.5 1.5 0 1 1 3 0v3.084A17.94 17.94 0 0 1 24 6c9.941 0 18 8.059 18 18s-8.059 18-18 18S6 33.941 6 24q.001-1.39.205-2.725a1.5 1.5 0 1 1 2.966.45Q9.001 22.837 9 24c0 8.284 6.716 15 15 15s15-6.716 15-15");
}

</style>
