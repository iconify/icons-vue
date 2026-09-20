<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dmpnh5lid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:likert-16-regular" /></template>
<style>
.dmpnh5lid {
  fill: currentColor;
  d: path("M7.25 5.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M6.5 11a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m2 0a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m2 0a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m2 0a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M1 5.5A2.5 2.5 0 0 1 3.5 3h9A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5zM3.5 4A1.5 1.5 0 0 0 2 5.5v2h2V4zM5 4v3.5h9v-2A1.5 1.5 0 0 0 12.5 4zM4 8.5H2v2A1.5 1.5 0 0 0 3.5 12H4zM5 12h7.5a1.5 1.5 0 0 0 1.5-1.5v-2H5z");
}

</style>
