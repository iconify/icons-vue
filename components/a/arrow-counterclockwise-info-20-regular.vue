<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2d3ptb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-info-20-regular" /></template>
<style>
.w2d3ptb5y {
  fill: currentColor;
  d: path("M16.988 9.594a5.5 5.5 0 0 0-1.042-.402A6.001 6.001 0 0 0 5.528 6H7.5a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 1 0v1.601a7 7 0 0 1 11.988 4.493M3 10a7 7 0 0 0 6.594 6.988a5.5 5.5 0 0 1-.402-1.042a6 6 0 0 1-5.174-6.408a.5.5 0 1 0-.998-.076Q3 9.73 3 10m7 4.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0m4.5 2.5a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5m0-5.125a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25");
}

</style>
