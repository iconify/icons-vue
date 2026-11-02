<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ataf4fbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-fill" /></template>
<style>
.ataf4fbxa {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm-3-1H9a1 1 0 0 0 0 2h1a1 1 0 0 0 0-2m-1 6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm6 4h-3a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2");
}

</style>
