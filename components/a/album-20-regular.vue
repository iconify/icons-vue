<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e8x7zabbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-20-regular" /></template>
<style>
.e8x7zabbw {
  fill: currentColor;
  d: path("M8 8.5A1.5 1.5 0 0 1 9.5 7h4A1.5 1.5 0 0 1 15 8.5v1a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8 9.5zM9.5 8a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zM2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm4 9h10a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H6zM5 5H4a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h1z");
}

</style>
