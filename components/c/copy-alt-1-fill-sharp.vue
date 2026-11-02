<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-e4o0euf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-fill-sharp" /></template>
<style>
.i-e4o0euf {
  fill: currentColor;
  d: path("M16 21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h5V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-5ZM10 4v4h5a1 1 0 0 1 1 1v5h4V4Z");
}

</style>
