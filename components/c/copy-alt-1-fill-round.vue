<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr1mw-09t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-fill-round" /></template>
<style>
.wr1mw-09t {
  fill: currentColor;
  d: path("M2 13a5 5 0 0 1 5-5h1V7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5h-1v1a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Zm15 1a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v1h1a5 5 0 0 1 5 5v1Z");
}

</style>
