<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oclz3kfak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-32-regular" /></template>
<style>
.oclz3kfak {
  fill: currentColor;
  d: path("M25.5 8.112A4.5 4.5 0 0 1 29 12.5v8a8.5 8.5 0 0 1-8.5 8.5h-8a4.5 4.5 0 0 1-4.387-3.5h2.097A2.5 2.5 0 0 0 12.5 27h8a6.5 6.5 0 0 0 6.5-6.5v-8a2.5 2.5 0 0 0-1.5-2.291zM19.5 3A4.5 4.5 0 0 1 24 7.5v12a4.5 4.5 0 0 1-4.5 4.5h-12A4.5 4.5 0 0 1 3 19.5v-6.408a3.24 3.24 0 0 0 2 0V19.5A2.5 2.5 0 0 0 7.5 22h12a2.5 2.5 0 0 0 2.5-2.5v-12A2.5 2.5 0 0 0 19.5 5h-12a2.5 2.5 0 0 0-2.433 1.93a3.25 3.25 0 0 0-2.026-.036A4.5 4.5 0 0 1 7.5 3zM4 8.25c.595 0 1.12.297 1.436.75h.012a6.86 6.86 0 0 1 5.621 2.927A4.86 4.86 0 0 0 15.052 14h2.034l-2.293-2.293a1 1 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a1 1 0 1 1-1.414-1.414L17.086 16h-2.034a6.86 6.86 0 0 1-5.621-2.927A4.86 4.86 0 0 0 5.448 11h-.012A1.75 1.75 0 1 1 4 8.25");
}

</style>
