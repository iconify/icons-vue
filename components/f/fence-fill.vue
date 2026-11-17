<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcybqpqkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fence-fill" /></template>
<style>
.xcybqpqkf {
  fill: currentColor;
  d: path("M4 17H3a1 1 0 0 1 0-2h1v-4H3a1 1 0 0 1 0-2h1V7c0-.155.036-.308.106-.447l1.552-3.106a1.5 1.5 0 0 1 2.684 0l1.552 3.106c.07.139.106.292.106.447v2h4V7c0-.155.036-.308.106-.447l1.552-3.106a1.5 1.5 0 0 1 2.684 0l1.552 3.106c.07.139.106.292.106.447v2h1a1 1 0 0 1 0 2h-1v4h1a1 1 0 0 1 0 2h-1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4h-4v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm10-2v-4h-4v4Z");
}

</style>
