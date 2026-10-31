<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbdo_152a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-32-regular" /></template>
<style>
.tbdo_152a {
  fill: currentColor;
  d: path("M10.5 11h-4A2.5 2.5 0 0 0 4 13.5v12A2.5 2.5 0 0 0 6.5 28h9a2.5 2.5 0 0 0 2.5-2.5v-1h2v1a4.5 4.5 0 0 1-4.5 4.5h-9A4.5 4.5 0 0 1 2 25.5v-12A4.5 4.5 0 0 1 6.5 9h4zm15-9A4.5 4.5 0 0 1 30 6.5v12a4.5 4.5 0 0 1-4.5 4.5h-9a4.5 4.5 0 0 1-4.5-4.5v-12A4.5 4.5 0 0 1 16.5 2zm-9 2A2.5 2.5 0 0 0 14 6.5v12a2.5 2.5 0 0 0 2.5 2.5h9a2.5 2.5 0 0 0 2.5-2.5v-12A2.5 2.5 0 0 0 25.5 4z");
}

</style>
