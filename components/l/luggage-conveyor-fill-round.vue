<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_gk0ikzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-fill-round" /></template>
<style>
.d_gk0ikzf {
  fill: currentColor;
  d: path("M8 6V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m6-2h-4v2h4ZM9 9v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0m4 0v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0M2 18a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm2 0v2h16v-2Z");
}

</style>
