<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gcxe63b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-select-20-regular" /></template>
<style>
.gcxe63b7r {
  fill: currentColor;
  d: path("M7 7H5.5A1.5 1.5 0 0 0 4 8.5v6A1.5 1.5 0 0 0 5.5 16h4a1.5 1.5 0 0 0 1.413-1h1.037a2.5 2.5 0 0 1-2.45 2h-4A2.5 2.5 0 0 1 3 14.5v-6A2.5 2.5 0 0 1 5.5 6H7zm1.5 4.5c.276 0 .492.23.582.491A1.5 1.5 0 0 0 10.5 13h.75a.5.5 0 0 1 0 1h-.75a2.5 2.5 0 0 1-2.45-2.003c-.055-.27.174-.497.45-.497m8 0c.276 0 .505.226.45.497A2.5 2.5 0 0 1 14.5 14h-.75a.5.5 0 0 1 0-1h.75c.656 0 1.215-.422 1.418-1.009c.09-.26.306-.491.582-.491M8.5 7a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5m8 0a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5m-5.25-4a.5.5 0 0 1 0 1h-.75a1.5 1.5 0 0 0-1.418 1.009c-.09.26-.306.491-.582.491s-.505-.226-.45-.497A2.5 2.5 0 0 1 10.5 3zm3.25 0a2.5 2.5 0 0 1 2.45 2.003c.055.27-.174.497-.45.497s-.492-.23-.582-.491A1.5 1.5 0 0 0 14.5 4h-.75a.5.5 0 0 1 0-1z");
}

</style>
