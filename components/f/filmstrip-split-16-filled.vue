<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s2kdpkbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-split-16-filled" /></template>
<style>
.s2kdpkbhw {
  fill: currentColor;
  d: path("M8.5 1.5a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zM1 5.5A2.5 2.5 0 0 1 3.5 3h3v10h-3A2.5 2.5 0 0 1 1 10.5zm2 0v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0M3.5 9a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m6 4V3h3A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5zM12 5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0m.5 3.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5");
}

</style>
