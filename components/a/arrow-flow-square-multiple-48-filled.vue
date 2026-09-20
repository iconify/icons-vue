<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mcba1qbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-48-filled" /></template>
<style>
.mcba1qbjf {
  fill: currentColor;
  d: path("M37 13.126c2.853.58 5 3.1 5 6.124v10.5C42 36.516 36.516 42 29.75 42h-10.5a6.25 6.25 0 0 1-6.125-5H28.75A8.25 8.25 0 0 0 37 28.75zM28.75 6A6.25 6.25 0 0 1 35 12.25v16.5A6.25 6.25 0 0 1 28.75 35h-16.5A6.25 6.25 0 0 1 6 28.75v-8.626a4.006 4.006 0 0 0 4.8-2.624h.817c2 0 3.867 1.01 4.962 2.684A8.43 8.43 0 0 0 23.633 24h3.1l-3.367 3.366a1.25 1.25 0 0 0 1.768 1.768l5.5-5.5a1.25 1.25 0 0 0 0-1.768l-5.5-5.5a1.25 1.25 0 0 0-1.768 1.768l3.366 3.366h-3.1c-2 0-3.866-1.01-4.961-2.684A8.43 8.43 0 0 0 11.617 15H10.8A4 4 0 0 0 6 12.376v-.126A6.25 6.25 0 0 1 12.25 6zM7 14.25a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
