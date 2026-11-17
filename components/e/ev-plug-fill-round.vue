<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_9wu2b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug-fill-round" /></template>
<style>
.y_9wu2b-t {
  fill: currentColor;
  d: path("M16.015 4a5 5 0 0 1 4.475 2.77a9.48 9.48 0 0 1-.032 8.525a9.5 9.5 0 0 1-4.889 4.496a9.4 9.4 0 0 1-3.569.694a9.4 9.4 0 0 1-3.569-.694a9.5 9.5 0 0 1-4.889-4.496A9.48 9.48 0 0 1 3.51 6.77A5 5 0 0 1 7.985 4ZM8 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M10 13a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
