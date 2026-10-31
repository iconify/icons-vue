<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v41fufb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-32-filled" /></template>
<style>
.v41fufb6i {
  fill: currentColor;
  d: path("M10.5 18.5a6 6 0 0 0 6 6H20v1a4.5 4.5 0 0 1-4.5 4.5h-9A4.5 4.5 0 0 1 2 25.5v-12A4.5 4.5 0 0 1 6.5 9h4zM25.5 2A4.5 4.5 0 0 1 30 6.5v12a4.5 4.5 0 0 1-4.5 4.5h-9a4.5 4.5 0 0 1-4.5-4.5v-12A4.5 4.5 0 0 1 16.5 2z");
}

</style>
