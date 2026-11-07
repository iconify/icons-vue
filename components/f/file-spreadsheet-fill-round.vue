<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge4oikb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-spreadsheet-fill-round" /></template>
<style>
.ge4oikb6c {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm-5 4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1Zm2 2v1H9v-1Zm2 1v-1h3v1Zm-2 2v1H9v-1Zm2 1v-1h3v1Z");
}

</style>
