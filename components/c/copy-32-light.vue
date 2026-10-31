<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_30n4sng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-32-light" /></template>
<style>
.j_30n4sng {
  fill: currentColor;
  d: path("M10.5 10h-4A3.5 3.5 0 0 0 3 13.5v12A3.5 3.5 0 0 0 6.5 29h9a3.5 3.5 0 0 0 3.5-3.5v-1h1v1a4.5 4.5 0 0 1-4.5 4.5h-9A4.5 4.5 0 0 1 2 25.5v-12A4.5 4.5 0 0 1 6.5 9h4zm15-8A4.5 4.5 0 0 1 30 6.5v12a4.5 4.5 0 0 1-4.5 4.5h-9a4.5 4.5 0 0 1-4.5-4.5v-12A4.5 4.5 0 0 1 16.5 2zm-9 1A3.5 3.5 0 0 0 13 6.5v12a3.5 3.5 0 0 0 3.5 3.5h9a3.5 3.5 0 0 0 3.5-3.5v-12A3.5 3.5 0 0 0 25.5 3z");
}

</style>
