<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvl7h2b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-save-off" /></template>
<style>
.nvl7h2b4x {
  fill: currentColor;
  d: path("M14 24v-2h5.175L12 14.825V20H6q-.825 0-1.412-.587T4 18V6.825L.7 3.5l1.4-1.4L22 22v2zm6.9-5.9l-1.4-1.425l1.1-1.1L22 17zM19 16.175l-2-2V13h2zM13.825 11L5.05 2.25q.225-.125.45-.187T6 2h7l6 6v3zM12 9h5l-5-5z");
}

</style>
