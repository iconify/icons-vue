<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s70agbb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-type-fill-round" /></template>
<style>
.s70agbb_z {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm-4 4a1 1 0 0 0 0 2h2v5a1 1 0 0 0 2 0v-5h2a1 1 0 0 0 0-2Z");
}

</style>
