<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="is6-hpbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-vertical-20-regular" /></template>
<style>
.is6-hpbam {
  fill: currentColor;
  d: path("M10.5 18a.5.5 0 0 1-.5-.5V16H8a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h2V9H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h4V2.5a.5.5 0 0 1 1 0V4h4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-4v2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-2v1.5a.5.5 0 0 1-.5.5M6 5a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm2 7a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1z");
}

</style>
