<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j37a_i7gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-32-filled" /></template>
<style>
.j37a_i7gg {
  fill: currentColor;
  d: path("M25.5 8.112A4.5 4.5 0 0 1 29 12.5v8a8.5 8.5 0 0 1-8.5 8.5h-8a4.5 4.5 0 0 1-4.387-3.5H19.5a6 6 0 0 0 6-6zM19.5 3A4.5 4.5 0 0 1 24 7.5v12a4.5 4.5 0 0 1-4.5 4.5h-12A4.5 4.5 0 0 1 3 19.5v-6.146a3.5 3.5 0 0 0 4.33-2.274a4.86 4.86 0 0 1 3.1 1.993A6.86 6.86 0 0 0 16.053 16h1.534l-2.293 2.293a1 1 0 1 0 1.414 1.414l4-4a1 1 0 0 0 0-1.414l-4-4a1 1 0 1 0-1.414 1.414L17.586 14h-1.534a4.86 4.86 0 0 1-3.983-2.073a6.86 6.86 0 0 0-4.697-2.863a3.5 3.5 0 0 0-4.286-2.443A4.5 4.5 0 0 1 7.5 3zM4 8.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
